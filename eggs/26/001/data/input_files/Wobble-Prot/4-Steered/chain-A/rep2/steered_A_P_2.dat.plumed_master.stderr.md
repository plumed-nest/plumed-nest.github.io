**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep2/steered_A_P_2.dat   
Download: [zipped raw stdout](steered_A_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04215] *** Process received signal ***
[runnervmmklqx:04215] Signal: Aborted (6)
[runnervmmklqx:04215] Signal code:  (-6)
[runnervmmklqx:04215] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd1dc845330]
[runnervmmklqx:04215] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd1dc89eb2c]
[runnervmmklqx:04215] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd1dc84527e]
[runnervmmklqx:04215] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd1dc8288ff]
[runnervmmklqx:04215] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd1dcca5ff5]
[runnervmmklqx:04215] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd1dccbb0da]
[runnervmmklqx:04215] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd1dcca5a55]
[runnervmmklqx:04215] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd1dcca5a6f]
[runnervmmklqx:04215] [ 8] plumed_master(+0x146dd)[0x55f540be86dd]
[runnervmmklqx:04215] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd1dc82a1ca]
[runnervmmklqx:04215] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd1dc82a28b]
[runnervmmklqx:04215] [11] plumed_master(+0x15365)[0x55f540be9365]
[runnervmmklqx:04215] *** End of error message ***
</pre>
{% endraw %}
