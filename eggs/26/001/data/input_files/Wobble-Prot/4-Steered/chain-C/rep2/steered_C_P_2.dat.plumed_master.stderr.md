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
[runnervmmklqx:04340] *** Process received signal ***
[runnervmmklqx:04340] Signal: Aborted (6)
[runnervmmklqx:04340] Signal code:  (-6)
[runnervmmklqx:04340] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fedc7445330]
[runnervmmklqx:04340] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fedc749eb2c]
[runnervmmklqx:04340] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fedc744527e]
[runnervmmklqx:04340] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fedc74288ff]
[runnervmmklqx:04340] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fedc78a5ff5]
[runnervmmklqx:04340] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fedc78bb0da]
[runnervmmklqx:04340] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fedc78a5a55]
[runnervmmklqx:04340] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fedc78a5a6f]
[runnervmmklqx:04340] [ 8] plumed_master(+0x146dd)[0x55c1bd2676dd]
[runnervmmklqx:04340] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fedc742a1ca]
[runnervmmklqx:04340] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fedc742a28b]
[runnervmmklqx:04340] [11] plumed_master(+0x15365)[0x55c1bd268365]
[runnervmmklqx:04340] *** End of error message ***
</pre>
{% endraw %}
