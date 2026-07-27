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
[runnervmvrwv9:04441] *** Process received signal ***
[runnervmvrwv9:04441] Signal: Aborted (6)
[runnervmvrwv9:04441] Signal code:  (-6)
[runnervmvrwv9:04441] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f177c245330]
[runnervmvrwv9:04441] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f177c29eb2c]
[runnervmvrwv9:04441] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f177c24527e]
[runnervmvrwv9:04441] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f177c2288ff]
[runnervmvrwv9:04441] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f177c6a5ff5]
[runnervmvrwv9:04441] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f177c6bb0da]
[runnervmvrwv9:04441] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f177c6a5a55]
[runnervmvrwv9:04441] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f177c6a5a6f]
[runnervmvrwv9:04441] [ 8] plumed_master(+0x146dd)[0x55f46cd566dd]
[runnervmvrwv9:04441] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f177c22a1ca]
[runnervmvrwv9:04441] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f177c22a28b]
[runnervmvrwv9:04441] [11] plumed_master(+0x15365)[0x55f46cd57365]
[runnervmvrwv9:04441] *** End of error message ***
</pre>
{% endraw %}
