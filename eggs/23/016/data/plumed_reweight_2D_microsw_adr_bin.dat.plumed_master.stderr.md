**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[runnervmeorf1:06303] *** Process received signal ***
[runnervmeorf1:06303] Signal: Aborted (6)
[runnervmeorf1:06303] Signal code:  (-6)
[runnervmeorf1:06303] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc3ef645330]
[runnervmeorf1:06303] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc3ef69eb2c]
[runnervmeorf1:06303] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc3ef64527e]
[runnervmeorf1:06303] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc3ef6288ff]
[runnervmeorf1:06303] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3efaa5ff5]
[runnervmeorf1:06303] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3efabb0da]
[runnervmeorf1:06303] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3efaa5a55]
[runnervmeorf1:06303] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3efaa5a6f]
[runnervmeorf1:06303] [ 8] plumed_master(+0x146dd)[0x5595a367f6dd]
[runnervmeorf1:06303] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc3ef62a1ca]
[runnervmeorf1:06303] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc3ef62a28b]
[runnervmeorf1:06303] [11] plumed_master(+0x15365)[0x5595a3680365]
[runnervmeorf1:06303] *** End of error message ***
</pre>
{% endraw %}
