**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-A/rep2/equil_A_P_2.dat   
Download: [zipped raw stdout](equil_A_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_A_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmgx7h7:04467] *** Process received signal ***
[runnervmgx7h7:04467] Signal: Aborted (6)
[runnervmgx7h7:04467] Signal code:  (-6)
[runnervmgx7h7:04467] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f52d1a45330]
[runnervmgx7h7:04467] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f52d1a9ec0c]
[runnervmgx7h7:04467] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f52d1a4527e]
[runnervmgx7h7:04467] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f52d1a288ff]
[runnervmgx7h7:04467] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f52d1ea5ff5]
[runnervmgx7h7:04467] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f52d1ebb0da]
[runnervmgx7h7:04467] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f52d1ea5a55]
[runnervmgx7h7:04467] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f52d1ea5a6f]
[runnervmgx7h7:04467] [ 8] plumed_master(+0x146dd)[0x55b371cff6dd]
[runnervmgx7h7:04467] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f52d1a2a1ca]
[runnervmgx7h7:04467] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f52d1a2a28b]
[runnervmgx7h7:04467] [11] plumed_master(+0x15365)[0x55b371d00365]
[runnervmgx7h7:04467] *** End of error message ***
</pre>
{% endraw %}
