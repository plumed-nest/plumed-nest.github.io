**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep1/equil_C_P_1.dat   
Download: [zipped raw stdout](equil_C_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_C_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04917] *** Process received signal ***
[runnervmmklqx:04917] Signal: Aborted (6)
[runnervmmklqx:04917] Signal code:  (-6)
[runnervmmklqx:04917] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb355e45330]
[runnervmmklqx:04917] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb355e9eb2c]
[runnervmmklqx:04917] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb355e4527e]
[runnervmmklqx:04917] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb355e288ff]
[runnervmmklqx:04917] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3562a5ff5]
[runnervmmklqx:04917] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3562bb0da]
[runnervmmklqx:04917] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3562a5a55]
[runnervmmklqx:04917] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3562a5a6f]
[runnervmmklqx:04917] [ 8] plumed_master(+0x146dd)[0x5573c30da6dd]
[runnervmmklqx:04917] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb355e2a1ca]
[runnervmmklqx:04917] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb355e2a28b]
[runnervmmklqx:04917] [11] plumed_master(+0x15365)[0x5573c30db365]
[runnervmmklqx:04917] *** End of error message ***
</pre>
{% endraw %}
