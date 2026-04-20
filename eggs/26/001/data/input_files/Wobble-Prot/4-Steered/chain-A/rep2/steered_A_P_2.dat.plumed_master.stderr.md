**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep2/steered_A_P_2.dat   
Download: [zipped raw stdout](steered_A_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:04423] *** Process received signal ***
[runnervmeorf1:04423] Signal: Aborted (6)
[runnervmeorf1:04423] Signal code:  (-6)
[runnervmeorf1:04423] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d7c445330]
[runnervmeorf1:04423] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d7c49eb2c]
[runnervmeorf1:04423] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d7c44527e]
[runnervmeorf1:04423] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d7c4288ff]
[runnervmeorf1:04423] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d7c8a5ff5]
[runnervmeorf1:04423] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d7c8bb0da]
[runnervmeorf1:04423] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d7c8a5a55]
[runnervmeorf1:04423] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d7c8a5a6f]
[runnervmeorf1:04423] [ 8] plumed_master(+0x146dd)[0x563181e746dd]
[runnervmeorf1:04423] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d7c42a1ca]
[runnervmeorf1:04423] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d7c42a28b]
[runnervmeorf1:04423] [11] plumed_master(+0x15365)[0x563181e75365]
[runnervmeorf1:04423] *** End of error message ***
</pre>
{% endraw %}
