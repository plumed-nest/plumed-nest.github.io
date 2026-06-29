**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep1/steered_D_P_1.dat   
Download: [zipped raw stdout](steered_D_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_D_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04555] *** Process received signal ***
[runnervmmklqx:04555] Signal: Aborted (6)
[runnervmmklqx:04555] Signal code:  (-6)
[runnervmmklqx:04555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca68645330]
[runnervmmklqx:04555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca6869eb2c]
[runnervmmklqx:04555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca6864527e]
[runnervmmklqx:04555] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca686288ff]
[runnervmmklqx:04555] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca68aa5ff5]
[runnervmmklqx:04555] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca68abb0da]
[runnervmmklqx:04555] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca68aa5a55]
[runnervmmklqx:04555] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca68aa5a6f]
[runnervmmklqx:04555] [ 8] plumed_master(+0x146dd)[0x55e5260076dd]
[runnervmmklqx:04555] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca6862a1ca]
[runnervmmklqx:04555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca6862a28b]
[runnervmmklqx:04555] [11] plumed_master(+0x15365)[0x55e526008365]
[runnervmmklqx:04555] *** End of error message ***
</pre>
{% endraw %}
