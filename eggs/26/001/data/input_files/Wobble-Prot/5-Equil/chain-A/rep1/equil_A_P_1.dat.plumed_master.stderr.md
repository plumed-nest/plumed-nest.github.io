**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-A/rep1/equil_A_P_1.dat   
Download: [zipped raw stdout](equil_A_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_A_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04763] *** Process received signal ***
[runnervmmklqx:04763] Signal: Aborted (6)
[runnervmmklqx:04763] Signal code:  (-6)
[runnervmmklqx:04763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f14f1045330]
[runnervmmklqx:04763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f14f109eb2c]
[runnervmmklqx:04763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f14f104527e]
[runnervmmklqx:04763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f14f10288ff]
[runnervmmklqx:04763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f14f14a5ff5]
[runnervmmklqx:04763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f14f14bb0da]
[runnervmmklqx:04763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f14f14a5a55]
[runnervmmklqx:04763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f14f14a5a6f]
[runnervmmklqx:04763] [ 8] plumed_master(+0x146dd)[0x55fc30cb36dd]
[runnervmmklqx:04763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f14f102a1ca]
[runnervmmklqx:04763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f14f102a28b]
[runnervmmklqx:04763] [11] plumed_master(+0x15365)[0x55fc30cb4365]
[runnervmmklqx:04763] *** End of error message ***
</pre>
{% endraw %}
