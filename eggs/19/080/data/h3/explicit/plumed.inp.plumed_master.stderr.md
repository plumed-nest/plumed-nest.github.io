**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/explicit/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmmklqx:10380] *** Process received signal ***
[runnervmmklqx:10380] Signal: Aborted (6)
[runnervmmklqx:10380] Signal code:  (-6)
[runnervmmklqx:10380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f90d6a45330]
[runnervmmklqx:10380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f90d6a9eb2c]
[runnervmmklqx:10380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f90d6a4527e]
[runnervmmklqx:10380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f90d6a288ff]
[runnervmmklqx:10380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90d6ea5ff5]
[runnervmmklqx:10380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90d6ebb0da]
[runnervmmklqx:10380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90d6ea5a55]
[runnervmmklqx:10380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90d6ea5a6f]
[runnervmmklqx:10380] [ 8] plumed_master(+0x146dd)[0x559e5ea316dd]
[runnervmmklqx:10380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f90d6a2a1ca]
[runnervmmklqx:10380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f90d6a2a28b]
[runnervmmklqx:10380] [11] plumed_master(+0x15365)[0x559e5ea32365]
[runnervmmklqx:10380] *** End of error message ***
</pre>
{% endraw %}
