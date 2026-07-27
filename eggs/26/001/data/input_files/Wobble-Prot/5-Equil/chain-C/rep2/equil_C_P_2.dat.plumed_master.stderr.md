**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/equil_C_P_2.dat   
Download: [zipped raw stdout](equil_C_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_C_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:04907] *** Process received signal ***
[runnervmvrwv9:04907] Signal: Aborted (6)
[runnervmvrwv9:04907] Signal code:  (-6)
[runnervmvrwv9:04907] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f948a245330]
[runnervmvrwv9:04907] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f948a29eb2c]
[runnervmvrwv9:04907] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f948a24527e]
[runnervmvrwv9:04907] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f948a2288ff]
[runnervmvrwv9:04907] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f948a6a5ff5]
[runnervmvrwv9:04907] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f948a6bb0da]
[runnervmvrwv9:04907] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f948a6a5a55]
[runnervmvrwv9:04907] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f948a6a5a6f]
[runnervmvrwv9:04907] [ 8] plumed_master(+0x146dd)[0x558df8ae26dd]
[runnervmvrwv9:04907] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f948a22a1ca]
[runnervmvrwv9:04907] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f948a22a28b]
[runnervmvrwv9:04907] [11] plumed_master(+0x15365)[0x558df8ae3365]
[runnervmvrwv9:04907] *** End of error message ***
</pre>
{% endraw %}
