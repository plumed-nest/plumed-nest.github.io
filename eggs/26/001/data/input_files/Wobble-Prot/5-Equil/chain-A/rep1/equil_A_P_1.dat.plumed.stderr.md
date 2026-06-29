**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-A/rep1/equil_A_P_1.dat   
Download: [zipped raw stdout](equil_A_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_A_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04748] *** Process received signal ***
[runnervmmklqx:04748] Signal: Aborted (6)
[runnervmmklqx:04748] Signal code:  (-6)
[runnervmmklqx:04748] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4254845330]
[runnervmmklqx:04748] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f425489eb2c]
[runnervmmklqx:04748] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f425484527e]
[runnervmmklqx:04748] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f42548288ff]
[runnervmmklqx:04748] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4254ca5ff5]
[runnervmmklqx:04748] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4254cbb0da]
[runnervmmklqx:04748] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4254ca5a55]
[runnervmmklqx:04748] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4254ca5a6f]
[runnervmmklqx:04748] [ 8] plumed(+0x146dd)[0x5558661c86dd]
[runnervmmklqx:04748] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f425482a1ca]
[runnervmmklqx:04748] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f425482a28b]
[runnervmmklqx:04748] [11] plumed(+0x15365)[0x5558661c9365]
[runnervmmklqx:04748] *** End of error message ***
</pre>
{% endraw %}
