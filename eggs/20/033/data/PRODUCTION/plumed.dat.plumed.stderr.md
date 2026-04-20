**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action WHOLEMOLECULES with label @5 : cannot understand the following words from the input line : REF0=16.995,21.964,24.520, REF1=26.253,18.440,24.5030, REF2=24.616,28.069,24.203
[runnervmeorf1:09179] *** Process received signal ***
[runnervmeorf1:09179] Signal: Aborted (6)
[runnervmeorf1:09179] Signal code:  (-6)
[runnervmeorf1:09179] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe367e45330]
[runnervmeorf1:09179] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe367e9eb2c]
[runnervmeorf1:09179] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe367e4527e]
[runnervmeorf1:09179] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe367e288ff]
[runnervmeorf1:09179] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3682a5ff5]
[runnervmeorf1:09179] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3682bb0da]
[runnervmeorf1:09179] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3682a5a55]
[runnervmeorf1:09179] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3682a5a6f]
[runnervmeorf1:09179] [ 8] plumed(+0x146dd)[0x561f68dc86dd]
[runnervmeorf1:09179] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe367e2a1ca]
[runnervmeorf1:09179] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe367e2a28b]
[runnervmeorf1:09179] [11] plumed(+0x15365)[0x561f68dc9365]
[runnervmeorf1:09179] *** End of error message ***
</pre>
{% endraw %}
