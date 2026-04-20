**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep1/equil_C_P_1.dat   
Download: [zipped raw stdout](equil_C_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_C_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:05098] *** Process received signal ***
[runnervmeorf1:05098] Signal: Aborted (6)
[runnervmeorf1:05098] Signal code:  (-6)
[runnervmeorf1:05098] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe0ef445330]
[runnervmeorf1:05098] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe0ef49eb2c]
[runnervmeorf1:05098] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe0ef44527e]
[runnervmeorf1:05098] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe0ef4288ff]
[runnervmeorf1:05098] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe0ef8a5ff5]
[runnervmeorf1:05098] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe0ef8bb0da]
[runnervmeorf1:05098] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe0ef8a5a55]
[runnervmeorf1:05098] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe0ef8a5a6f]
[runnervmeorf1:05098] [ 8] plumed_master(+0x146dd)[0x55df22bb76dd]
[runnervmeorf1:05098] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe0ef42a1ca]
[runnervmeorf1:05098] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe0ef42a28b]
[runnervmeorf1:05098] [11] plumed_master(+0x15365)[0x55df22bb8365]
[runnervmeorf1:05098] *** End of error message ***
</pre>
{% endraw %}
