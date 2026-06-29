**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep2/steered_B_P_2.dat   
Download: [zipped raw stdout](steered_B_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_B_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04606] *** Process received signal ***
[runnervmmklqx:04606] Signal: Aborted (6)
[runnervmmklqx:04606] Signal code:  (-6)
[runnervmmklqx:04606] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f56a45330]
[runnervmmklqx:04606] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f56a9eb2c]
[runnervmmklqx:04606] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f56a4527e]
[runnervmmklqx:04606] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f56a288ff]
[runnervmmklqx:04606] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f56ea5ff5]
[runnervmmklqx:04606] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f56ebb0da]
[runnervmmklqx:04606] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f56ea5a55]
[runnervmmklqx:04606] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f56ea5a6f]
[runnervmmklqx:04606] [ 8] plumed_master(+0x146dd)[0x5566db9dc6dd]
[runnervmmklqx:04606] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f56a2a1ca]
[runnervmmklqx:04606] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f56a2a28b]
[runnervmmklqx:04606] [11] plumed_master(+0x15365)[0x5566db9dd365]
[runnervmmklqx:04606] *** End of error message ***
</pre>
{% endraw %}
