**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep2/steered_A_2.dat   
Download: [zipped raw stdout](steered_A_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmmklqx:05177] *** Process received signal ***
[runnervmmklqx:05177] Signal: Aborted (6)
[runnervmmklqx:05177] Signal code:  (-6)
[runnervmmklqx:05177] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f55f5c45330]
[runnervmmklqx:05177] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f55f5c9eb2c]
[runnervmmklqx:05177] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f55f5c4527e]
[runnervmmklqx:05177] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55f5c288ff]
[runnervmmklqx:05177] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55f60a5ff5]
[runnervmmklqx:05177] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55f60bb0da]
[runnervmmklqx:05177] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55f60a5a55]
[runnervmmklqx:05177] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55f60a5a6f]
[runnervmmklqx:05177] [ 8] plumed_master(+0x146dd)[0x56110f0eb6dd]
[runnervmmklqx:05177] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f55f5c2a1ca]
[runnervmmklqx:05177] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f55f5c2a28b]
[runnervmmklqx:05177] [11] plumed_master(+0x15365)[0x56110f0ec365]
[runnervmmklqx:05177] *** End of error message ***
</pre>
{% endraw %}
