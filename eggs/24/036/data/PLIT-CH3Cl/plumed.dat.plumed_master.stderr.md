**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmeorf1:05044] *** Process received signal ***
[runnervmeorf1:05044] Signal: Aborted (6)
[runnervmeorf1:05044] Signal code:  (-6)
[runnervmeorf1:05044] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faae1c45330]
[runnervmeorf1:05044] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faae1c9eb2c]
[runnervmeorf1:05044] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faae1c4527e]
[runnervmeorf1:05044] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faae1c288ff]
[runnervmeorf1:05044] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faae20a5ff5]
[runnervmeorf1:05044] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faae20bb0da]
[runnervmeorf1:05044] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faae20a5a55]
[runnervmeorf1:05044] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faae20a5a6f]
[runnervmeorf1:05044] [ 8] plumed_master(+0x146dd)[0x55a4490f36dd]
[runnervmeorf1:05044] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faae1c2a1ca]
[runnervmeorf1:05044] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faae1c2a28b]
[runnervmeorf1:05044] [11] plumed_master(+0x15365)[0x55a4490f4365]
[runnervmeorf1:05044] *** End of error message ***
</pre>
{% endraw %}
