**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-B/rep1/equil_B_P_1.dat   
Download: [zipped raw stdout](equil_B_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_B_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:05125] *** Process received signal ***
[runnervmmklqx:05125] Signal: Aborted (6)
[runnervmmklqx:05125] Signal code:  (-6)
[runnervmmklqx:05125] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f22f8645330]
[runnervmmklqx:05125] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f22f869eb2c]
[runnervmmklqx:05125] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f22f864527e]
[runnervmmklqx:05125] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22f86288ff]
[runnervmmklqx:05125] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22f8aa5ff5]
[runnervmmklqx:05125] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22f8abb0da]
[runnervmmklqx:05125] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22f8aa5a55]
[runnervmmklqx:05125] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22f8aa5a6f]
[runnervmmklqx:05125] [ 8] plumed_master(+0x146dd)[0x557e29de46dd]
[runnervmmklqx:05125] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f22f862a1ca]
[runnervmmklqx:05125] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f22f862a28b]
[runnervmmklqx:05125] [11] plumed_master(+0x15365)[0x557e29de5365]
[runnervmmklqx:05125] *** End of error message ***
</pre>
{% endraw %}
