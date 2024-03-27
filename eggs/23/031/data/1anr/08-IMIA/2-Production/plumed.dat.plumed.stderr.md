**Project ID:** [plumID:23.031]({{ '/' | absolute_url }}eggs/23/031/)  
Stderr for source:  1anr/08-IMIA/2-Production/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: SHADOW LABEL=rmsd ATOMS=rna NOPBC UPDATE=100
Maybe a missing space or a typo?
[fv-az1487-606:68482] *** Process received signal ***
[fv-az1487-606:68482] Signal: Aborted (6)
[fv-az1487-606:68482] Signal code:  (-6)
[fv-az1487-606:68482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd1a1e42520]
[fv-az1487-606:68482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd1a1e969fc]
[fv-az1487-606:68482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd1a1e42476]
[fv-az1487-606:68482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd1a1e287f3]
[fv-az1487-606:68482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fd1a22a4f26]
[fv-az1487-606:68482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fd1a22b6d9c]
[fv-az1487-606:68482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fd1a22b6e07]
[fv-az1487-606:68482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd1a22b70bb]
[fv-az1487-606:68482] [ 8] plumed(+0x12f48)[0x557757eb6f48]
[fv-az1487-606:68482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd1a1e29d90]
[fv-az1487-606:68482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd1a1e29e40]
[fv-az1487-606:68482] [11] plumed(+0x131e5)[0x557757eb71e5]
[fv-az1487-606:68482] *** End of error message ***
</pre>
{% endraw %}
