**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @50 : keyword ARG is compulsory for this action
[runnervmeorf1:07858] *** Process received signal ***
[runnervmeorf1:07858] Signal: Aborted (6)
[runnervmeorf1:07858] Signal code:  (-6)
[runnervmeorf1:07858] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7eae245330]
[runnervmeorf1:07858] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7eae29eb2c]
[runnervmeorf1:07858] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7eae24527e]
[runnervmeorf1:07858] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7eae2288ff]
[runnervmeorf1:07858] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7eae6a5ff5]
[runnervmeorf1:07858] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7eae6bb0da]
[runnervmeorf1:07858] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7eae6a5a55]
[runnervmeorf1:07858] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7eae6a5a6f]
[runnervmeorf1:07858] [ 8] plumed_master(+0x146dd)[0x5635f888b6dd]
[runnervmeorf1:07858] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7eae22a1ca]
[runnervmeorf1:07858] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7eae22a28b]
[runnervmeorf1:07858] [11] plumed_master(+0x15365)[0x5635f888c365]
[runnervmeorf1:07858] *** End of error message ***
</pre>
{% endraw %}
