**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-D/rep1/equil_D_P_1.dat   
Download: [zipped raw stdout](equil_D_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_D_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:05114] *** Process received signal ***
[runnervmvrwv9:05114] Signal: Aborted (6)
[runnervmvrwv9:05114] Signal code:  (-6)
[runnervmvrwv9:05114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdddc445330]
[runnervmvrwv9:05114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdddc49eb2c]
[runnervmvrwv9:05114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdddc44527e]
[runnervmvrwv9:05114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdddc4288ff]
[runnervmvrwv9:05114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdddc8a5ff5]
[runnervmvrwv9:05114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdddc8bb0da]
[runnervmvrwv9:05114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdddc8a5a55]
[runnervmvrwv9:05114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdddc8a5a6f]
[runnervmvrwv9:05114] [ 8] plumed_master(+0x146dd)[0x5609064446dd]
[runnervmvrwv9:05114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdddc42a1ca]
[runnervmvrwv9:05114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdddc42a28b]
[runnervmvrwv9:05114] [11] plumed_master(+0x15365)[0x560906445365]
[runnervmvrwv9:05114] *** End of error message ***
</pre>
{% endraw %}
