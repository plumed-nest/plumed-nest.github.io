**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep2/steered_D_P_2.dat   
Download: [zipped raw stdout](steered_D_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_D_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmgx7h7:04260] *** Process received signal ***
[runnervmgx7h7:04260] Signal: Aborted (6)
[runnervmgx7h7:04260] Signal code:  (-6)
[runnervmgx7h7:04260] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4661245330]
[runnervmgx7h7:04260] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f466129ec0c]
[runnervmgx7h7:04260] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f466124527e]
[runnervmgx7h7:04260] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46612288ff]
[runnervmgx7h7:04260] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46616a5ff5]
[runnervmgx7h7:04260] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46616bb0da]
[runnervmgx7h7:04260] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46616a5a55]
[runnervmgx7h7:04260] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46616a5a6f]
[runnervmgx7h7:04260] [ 8] plumed_master(+0x146dd)[0x5558797606dd]
[runnervmgx7h7:04260] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f466122a1ca]
[runnervmgx7h7:04260] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f466122a28b]
[runnervmgx7h7:04260] [11] plumed_master(+0x15365)[0x555879761365]
[runnervmgx7h7:04260] *** End of error message ***
</pre>
{% endraw %}
