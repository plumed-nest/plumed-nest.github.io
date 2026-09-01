**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/steered_C_P_2.dat   
Download: [zipped raw stdout](steered_C_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_C_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmgx7h7:04105] *** Process received signal ***
[runnervmgx7h7:04105] Signal: Aborted (6)
[runnervmgx7h7:04105] Signal code:  (-6)
[runnervmgx7h7:04105] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe1c045330]
[runnervmgx7h7:04105] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe1c09ec0c]
[runnervmgx7h7:04105] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe1c04527e]
[runnervmgx7h7:04105] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe1c0288ff]
[runnervmgx7h7:04105] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe1c4a5ff5]
[runnervmgx7h7:04105] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe1c4bb0da]
[runnervmgx7h7:04105] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe1c4a5a55]
[runnervmgx7h7:04105] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe1c4a5a6f]
[runnervmgx7h7:04105] [ 8] plumed_master(+0x146dd)[0x55c8cdeac6dd]
[runnervmgx7h7:04105] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe1c02a1ca]
[runnervmgx7h7:04105] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe1c02a28b]
[runnervmgx7h7:04105] [11] plumed_master(+0x15365)[0x55c8cdead365]
[runnervmgx7h7:04105] *** End of error message ***
</pre>
{% endraw %}
