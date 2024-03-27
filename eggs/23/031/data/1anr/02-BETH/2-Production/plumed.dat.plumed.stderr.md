**Project ID:** [plumID:23.031]({{ '/' | absolute_url }}eggs/23/031/)  
Stderr for source:  1anr/02-BETH/2-Production/plumed.dat   
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
[fv-az1487-606:68299] *** Process received signal ***
[fv-az1487-606:68299] Signal: Aborted (6)
[fv-az1487-606:68299] Signal code:  (-6)
[fv-az1487-606:68299] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdf11e42520]
[fv-az1487-606:68299] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdf11e969fc]
[fv-az1487-606:68299] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdf11e42476]
[fv-az1487-606:68299] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdf11e287f3]
[fv-az1487-606:68299] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fdf122a4f26]
[fv-az1487-606:68299] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fdf122b6d9c]
[fv-az1487-606:68299] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fdf122b6e07]
[fv-az1487-606:68299] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdf122b70bb]
[fv-az1487-606:68299] [ 8] plumed(+0x12f48)[0x561a2481ef48]
[fv-az1487-606:68299] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdf11e29d90]
[fv-az1487-606:68299] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdf11e29e40]
[fv-az1487-606:68299] [11] plumed(+0x131e5)[0x561a2481f1e5]
[fv-az1487-606:68299] *** End of error message ***
</pre>
{% endraw %}
