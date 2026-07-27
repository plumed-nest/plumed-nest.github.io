**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-A/rep2/equil_A_P_2.dat   
Download: [zipped raw stdout](equil_A_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_A_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:04787] *** Process received signal ***
[runnervmvrwv9:04787] Signal: Aborted (6)
[runnervmvrwv9:04787] Signal code:  (-6)
[runnervmvrwv9:04787] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f505a445330]
[runnervmvrwv9:04787] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f505a49eb2c]
[runnervmvrwv9:04787] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f505a44527e]
[runnervmvrwv9:04787] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f505a4288ff]
[runnervmvrwv9:04787] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f505a8a5ff5]
[runnervmvrwv9:04787] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f505a8bb0da]
[runnervmvrwv9:04787] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f505a8a5a55]
[runnervmvrwv9:04787] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f505a8a5a6f]
[runnervmvrwv9:04787] [ 8] plumed(+0x146dd)[0x561416cd66dd]
[runnervmvrwv9:04787] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f505a42a1ca]
[runnervmvrwv9:04787] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f505a42a28b]
[runnervmvrwv9:04787] [11] plumed(+0x15365)[0x561416cd7365]
[runnervmvrwv9:04787] *** End of error message ***
</pre>
{% endraw %}
