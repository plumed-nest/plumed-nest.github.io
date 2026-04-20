**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmeorf1:08436] *** Process received signal ***
[runnervmeorf1:08436] Signal: Aborted (6)
[runnervmeorf1:08436] Signal code:  (-6)
[runnervmeorf1:08436] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffbae045330]
[runnervmeorf1:08436] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffbae09eb2c]
[runnervmeorf1:08436] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffbae04527e]
[runnervmeorf1:08436] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffbae0288ff]
[runnervmeorf1:08436] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffbae4a5ff5]
[runnervmeorf1:08436] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffbae4bb0da]
[runnervmeorf1:08436] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffbae4a5a55]
[runnervmeorf1:08436] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffbae4a5a6f]
[runnervmeorf1:08436] [ 8] plumed_master(+0x146dd)[0x56255cf556dd]
[runnervmeorf1:08436] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffbae02a1ca]
[runnervmeorf1:08436] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffbae02a28b]
[runnervmeorf1:08436] [11] plumed_master(+0x15365)[0x56255cf56365]
[runnervmeorf1:08436] *** End of error message ***
</pre>
{% endraw %}
