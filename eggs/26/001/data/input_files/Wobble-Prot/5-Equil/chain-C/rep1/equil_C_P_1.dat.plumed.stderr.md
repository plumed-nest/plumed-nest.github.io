**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep1/equil_C_P_1.dat   
Download: [zipped raw stdout](equil_C_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_C_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:04995] *** Process received signal ***
[runnervmvrwv9:04995] Signal: Aborted (6)
[runnervmvrwv9:04995] Signal code:  (-6)
[runnervmvrwv9:04995] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe33e645330]
[runnervmvrwv9:04995] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe33e69eb2c]
[runnervmvrwv9:04995] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe33e64527e]
[runnervmvrwv9:04995] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe33e6288ff]
[runnervmvrwv9:04995] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe33eaa5ff5]
[runnervmvrwv9:04995] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe33eabb0da]
[runnervmvrwv9:04995] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe33eaa5a55]
[runnervmvrwv9:04995] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe33eaa5a6f]
[runnervmvrwv9:04995] [ 8] plumed(+0x146dd)[0x555e6939c6dd]
[runnervmvrwv9:04995] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe33e62a1ca]
[runnervmvrwv9:04995] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe33e62a28b]
[runnervmvrwv9:04995] [11] plumed(+0x15365)[0x555e6939d365]
[runnervmvrwv9:04995] *** End of error message ***
</pre>
{% endraw %}
