**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-D/rep2/equil_D_P_2.dat   
Download: [zipped raw stdout](equil_D_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_D_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:05149] *** Process received signal ***
[runnervmeorf1:05149] Signal: Aborted (6)
[runnervmeorf1:05149] Signal code:  (-6)
[runnervmeorf1:05149] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f981fe45330]
[runnervmeorf1:05149] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f981fe9eb2c]
[runnervmeorf1:05149] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f981fe4527e]
[runnervmeorf1:05149] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f981fe288ff]
[runnervmeorf1:05149] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98202a5ff5]
[runnervmeorf1:05149] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98202bb0da]
[runnervmeorf1:05149] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98202a5a55]
[runnervmeorf1:05149] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98202a5a6f]
[runnervmeorf1:05149] [ 8] plumed_master(+0x146dd)[0x55e0aebfd6dd]
[runnervmeorf1:05149] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f981fe2a1ca]
[runnervmeorf1:05149] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f981fe2a28b]
[runnervmeorf1:05149] [11] plumed_master(+0x15365)[0x55e0aebfe365]
[runnervmeorf1:05149] *** End of error message ***
</pre>
{% endraw %}
