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
[fv-az695-955:08278] *** Process received signal ***
[fv-az695-955:08278] Signal: Aborted (6)
[fv-az695-955:08278] Signal code:  (-6)
[fv-az695-955:08278] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe648e42520]
[fv-az695-955:08278] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe648e969fc]
[fv-az695-955:08278] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe648e42476]
[fv-az695-955:08278] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe648e287f3]
[fv-az695-955:08278] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe6492a2b9e]
[fv-az695-955:08278] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe6492ae20c]
[fv-az695-955:08278] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe6492ae277]
[fv-az695-955:08278] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe6492ae52b]
[fv-az695-955:08278] [ 8] plumed(+0x12f48)[0x55729cf5ef48]
[fv-az695-955:08278] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe648e29d90]
[fv-az695-955:08278] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe648e29e40]
[fv-az695-955:08278] [11] plumed(+0x131e5)[0x55729cf5f1e5]
[fv-az695-955:08278] *** End of error message ***
</pre>
{% endraw %}
