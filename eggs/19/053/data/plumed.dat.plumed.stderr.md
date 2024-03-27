**Project ID:** [plumID:19.053]({{ '/' | absolute_url }}eggs/19/053/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: MORE_THAN LABEL=smapfcc ARG=fcc SWITCH=SMAP R_0=0.5 A=8 B=8
Maybe a missing space or a typo?
[fv-az1210-136:71763] *** Process received signal ***
[fv-az1210-136:71763] Signal: Aborted (6)
[fv-az1210-136:71763] Signal code:  (-6)
[fv-az1210-136:71763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f66ef242520]
[fv-az1210-136:71763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f66ef2969fc]
[fv-az1210-136:71763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f66ef242476]
[fv-az1210-136:71763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f66ef2287f3]
[fv-az1210-136:71763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f66ef6a4f26]
[fv-az1210-136:71763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f66ef6b6d9c]
[fv-az1210-136:71763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f66ef6b6e07]
[fv-az1210-136:71763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f66ef6b70bb]
[fv-az1210-136:71763] [ 8] plumed(+0x12f48)[0x5601261fcf48]
[fv-az1210-136:71763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f66ef229d90]
[fv-az1210-136:71763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f66ef229e40]
[fv-az1210-136:71763] [11] plumed(+0x131e5)[0x5601261fd1e5]
[fv-az1210-136:71763] *** End of error message ***
</pre>
{% endraw %}
