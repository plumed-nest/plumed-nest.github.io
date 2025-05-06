**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[fv-az807-718:61208] *** Process received signal ***
[fv-az807-718:61208] Signal: Aborted (6)
[fv-az807-718:61208] Signal code:  (-6)
[fv-az807-718:61208] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd716245330]
[fv-az807-718:61208] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd71629eb2c]
[fv-az807-718:61208] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd71624527e]
[fv-az807-718:61208] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7162288ff]
[fv-az807-718:61208] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7166a5ff5]
[fv-az807-718:61208] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7166bb0da]
[fv-az807-718:61208] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7166a5a55]
[fv-az807-718:61208] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7166a5a6f]
[fv-az807-718:61208] [ 8] plumed_master(+0x146dd)[0x55e2506276dd]
[fv-az807-718:61208] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd71622a1ca]
[fv-az807-718:61208] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd71622a28b]
[fv-az807-718:61208] [11] plumed_master(+0x15365)[0x55e250628365]
[fv-az807-718:61208] *** End of error message ***
</pre>
{% endraw %}
