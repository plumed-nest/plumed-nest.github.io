**Project ID:** [plumID:23.005]({{ '/' | absolute_url }}eggs/23/005/)  
Stderr for source:  apo-5HT1A/plumed_reweight_2D_microsw_5ht1a_rec.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_5ht1a_rec.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @60 : keyword ARG is compulsory for this action
[runnervmmtnos:33514] *** Process received signal ***
[runnervmmtnos:33514] Signal: Aborted (6)
[runnervmmtnos:33514] Signal code:  (-6)
[runnervmmtnos:33514] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9602e45330]
[runnervmmtnos:33514] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9602e9eb2c]
[runnervmmtnos:33514] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9602e4527e]
[runnervmmtnos:33514] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9602e288ff]
[runnervmmtnos:33514] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f96032a5ff5]
[runnervmmtnos:33514] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f96032bb0da]
[runnervmmtnos:33514] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f96032a5a55]
[runnervmmtnos:33514] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f96032a5a6f]
[runnervmmtnos:33514] [ 8] plumed_master(+0x146dd)[0x557795f9a6dd]
[runnervmmtnos:33514] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9602e2a1ca]
[runnervmmtnos:33514] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9602e2a28b]
[runnervmmtnos:33514] [11] plumed_master(+0x15365)[0x557795f9b365]
[runnervmmtnos:33514] *** End of error message ***
</pre>
{% endraw %}
