**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep1/steered_C_P_1.dat   
Download: [zipped raw stdout](steered_C_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_C_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04450] *** Process received signal ***
[runnervmmklqx:04450] Signal: Aborted (6)
[runnervmmklqx:04450] Signal code:  (-6)
[runnervmmklqx:04450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f04be045330]
[runnervmmklqx:04450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f04be09eb2c]
[runnervmmklqx:04450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f04be04527e]
[runnervmmklqx:04450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f04be0288ff]
[runnervmmklqx:04450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f04be4a5ff5]
[runnervmmklqx:04450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f04be4bb0da]
[runnervmmklqx:04450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f04be4a5a55]
[runnervmmklqx:04450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f04be4a5a6f]
[runnervmmklqx:04450] [ 8] plumed_master(+0x146dd)[0x5566ca99c6dd]
[runnervmmklqx:04450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f04be02a1ca]
[runnervmmklqx:04450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f04be02a28b]
[runnervmmklqx:04450] [11] plumed_master(+0x15365)[0x5566ca99d365]
[runnervmmklqx:04450] *** End of error message ***
</pre>
{% endraw %}
