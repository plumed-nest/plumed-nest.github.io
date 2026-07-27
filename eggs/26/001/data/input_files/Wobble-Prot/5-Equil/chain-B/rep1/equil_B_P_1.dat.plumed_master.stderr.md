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
[runnervmvrwv9:05217] *** Process received signal ***
[runnervmvrwv9:05217] Signal: Aborted (6)
[runnervmvrwv9:05217] Signal code:  (-6)
[runnervmvrwv9:05217] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41cdc45330]
[runnervmvrwv9:05217] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41cdc9eb2c]
[runnervmvrwv9:05217] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41cdc4527e]
[runnervmvrwv9:05217] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41cdc288ff]
[runnervmvrwv9:05217] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41ce0a5ff5]
[runnervmvrwv9:05217] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41ce0bb0da]
[runnervmvrwv9:05217] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41ce0a5a55]
[runnervmvrwv9:05217] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41ce0a5a6f]
[runnervmvrwv9:05217] [ 8] plumed_master(+0x146dd)[0x55bc0f5e56dd]
[runnervmvrwv9:05217] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41cdc2a1ca]
[runnervmvrwv9:05217] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41cdc2a28b]
[runnervmvrwv9:05217] [11] plumed_master(+0x15365)[0x55bc0f5e6365]
[runnervmvrwv9:05217] *** End of error message ***
</pre>
{% endraw %}
