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
[fv-az693-738:08230] *** Process received signal ***
[fv-az693-738:08230] Signal: Aborted (6)
[fv-az693-738:08230] Signal code:  (-6)
[fv-az693-738:08230] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f2e6d042520]
[fv-az693-738:08230] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f2e6d0969fc]
[fv-az693-738:08230] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f2e6d042476]
[fv-az693-738:08230] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f2e6d0287f3]
[fv-az693-738:08230] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f2e6d4a2b9e]
[fv-az693-738:08230] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f2e6d4ae20c]
[fv-az693-738:08230] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f2e6d4ae277]
[fv-az693-738:08230] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f2e6d4ae52b]
[fv-az693-738:08230] [ 8] plumed(+0x12f48)[0x556502c39f48]
[fv-az693-738:08230] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f2e6d029d90]
[fv-az693-738:08230] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f2e6d029e40]
[fv-az693-738:08230] [11] plumed(+0x131e5)[0x556502c3a1e5]
[fv-az693-738:08230] *** End of error message ***
</pre>
{% endraw %}
