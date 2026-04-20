**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmeorf1:04920] *** Process received signal ***
[runnervmeorf1:04920] Signal: Aborted (6)
[runnervmeorf1:04920] Signal code:  (-6)
[runnervmeorf1:04920] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c69e45330]
[runnervmeorf1:04920] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c69e9eb2c]
[runnervmeorf1:04920] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c69e4527e]
[runnervmeorf1:04920] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c69e288ff]
[runnervmeorf1:04920] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c6a2a5ff5]
[runnervmeorf1:04920] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c6a2bb0da]
[runnervmeorf1:04920] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c6a2a5a55]
[runnervmeorf1:04920] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c6a2a5a6f]
[runnervmeorf1:04920] [ 8] plumed_master(+0x146dd)[0x555c840af6dd]
[runnervmeorf1:04920] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c69e2a1ca]
[runnervmeorf1:04920] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c69e2a28b]
[runnervmeorf1:04920] [11] plumed_master(+0x15365)[0x555c840b0365]
[runnervmeorf1:04920] *** End of error message ***
</pre>
{% endraw %}
