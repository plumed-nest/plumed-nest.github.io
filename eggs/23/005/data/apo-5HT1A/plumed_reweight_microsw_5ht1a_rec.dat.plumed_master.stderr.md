**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @73 : keyword ARG is compulsory for this action
[runnervmmtnos:33555] *** Process received signal ***
[runnervmmtnos:33555] Signal: Aborted (6)
[runnervmmtnos:33555] Signal code:  (-6)
[runnervmmtnos:33555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2192a45330]
[runnervmmtnos:33555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2192a9eb2c]
[runnervmmtnos:33555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2192a4527e]
[runnervmmtnos:33555] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2192a288ff]
[runnervmmtnos:33555] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2192ea5ff5]
[runnervmmtnos:33555] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2192ebb0da]
[runnervmmtnos:33555] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2192ea5a55]
[runnervmmtnos:33555] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2192ea5a6f]
[runnervmmtnos:33555] [ 8] plumed_master(+0x146dd)[0x55565c9946dd]
[runnervmmtnos:33555] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2192a2a1ca]
[runnervmmtnos:33555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2192a2a28b]
[runnervmmtnos:33555] [11] plumed_master(+0x15365)[0x55565c995365]
[runnervmmtnos:33555] *** End of error message ***
</pre>
{% endraw %}
