**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-B/rep1/equil_B_P_1.dat   
Download: [zipped raw stdout](equil_B_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_B_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmgx7h7:04866] *** Process received signal ***
[runnervmgx7h7:04866] Signal: Aborted (6)
[runnervmgx7h7:04866] Signal code:  (-6)
[runnervmgx7h7:04866] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5bcf245330]
[runnervmgx7h7:04866] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5bcf29ec0c]
[runnervmgx7h7:04866] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5bcf24527e]
[runnervmgx7h7:04866] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5bcf2288ff]
[runnervmgx7h7:04866] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5bcf6a5ff5]
[runnervmgx7h7:04866] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5bcf6bb0da]
[runnervmgx7h7:04866] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5bcf6a5a55]
[runnervmgx7h7:04866] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5bcf6a5a6f]
[runnervmgx7h7:04866] [ 8] plumed(+0x146dd)[0x55ef015b16dd]
[runnervmgx7h7:04866] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5bcf22a1ca]
[runnervmgx7h7:04866] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5bcf22a28b]
[runnervmgx7h7:04866] [11] plumed(+0x15365)[0x55ef015b2365]
[runnervmgx7h7:04866] *** End of error message ***
</pre>
{% endraw %}
