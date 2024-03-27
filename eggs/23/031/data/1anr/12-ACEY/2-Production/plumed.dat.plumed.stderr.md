**Project ID:** [plumID:23.031]({{ '/' | absolute_url }}eggs/23/031/)  
Stderr for source:  1anr/12-ACEY/2-Production/plumed.dat   
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
[fv-az1487-606:68611] *** Process received signal ***
[fv-az1487-606:68611] Signal: Aborted (6)
[fv-az1487-606:68611] Signal code:  (-6)
[fv-az1487-606:68611] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff0ab042520]
[fv-az1487-606:68611] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff0ab0969fc]
[fv-az1487-606:68611] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff0ab042476]
[fv-az1487-606:68611] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff0ab0287f3]
[fv-az1487-606:68611] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7ff0ab4a4f26]
[fv-az1487-606:68611] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7ff0ab4b6d9c]
[fv-az1487-606:68611] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7ff0ab4b6e07]
[fv-az1487-606:68611] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff0ab4b70bb]
[fv-az1487-606:68611] [ 8] plumed(+0x12f48)[0x5611e095ef48]
[fv-az1487-606:68611] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff0ab029d90]
[fv-az1487-606:68611] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff0ab029e40]
[fv-az1487-606:68611] [11] plumed(+0x131e5)[0x5611e095f1e5]
[fv-az1487-606:68611] *** End of error message ***
</pre>
{% endraw %}
