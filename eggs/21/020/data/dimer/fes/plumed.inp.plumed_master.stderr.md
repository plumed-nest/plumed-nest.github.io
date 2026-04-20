**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[runnervmeorf1:08220] *** Process received signal ***
[runnervmeorf1:08220] Signal: Aborted (6)
[runnervmeorf1:08220] Signal code:  (-6)
[runnervmeorf1:08220] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9d2f045330]
[runnervmeorf1:08220] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9d2f09eb2c]
[runnervmeorf1:08220] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9d2f04527e]
[runnervmeorf1:08220] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9d2f0288ff]
[runnervmeorf1:08220] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9d2f4a5ff5]
[runnervmeorf1:08220] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9d2f4bb0da]
[runnervmeorf1:08220] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9d2f4a5a55]
[runnervmeorf1:08220] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9d2f4a5a6f]
[runnervmeorf1:08220] [ 8] plumed_master(+0x146dd)[0x5558255656dd]
[runnervmeorf1:08220] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9d2f02a1ca]
[runnervmeorf1:08220] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9d2f02a28b]
[runnervmeorf1:08220] [11] plumed_master(+0x15365)[0x555825566365]
[runnervmeorf1:08220] *** End of error message ***
</pre>
{% endraw %}
