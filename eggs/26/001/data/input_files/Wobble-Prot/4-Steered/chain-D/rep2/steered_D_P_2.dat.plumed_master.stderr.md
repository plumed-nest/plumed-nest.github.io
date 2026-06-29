**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep2/steered_D_P_2.dat   
Download: [zipped raw stdout](steered_D_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_D_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04501] *** Process received signal ***
[runnervmmklqx:04501] Signal: Aborted (6)
[runnervmmklqx:04501] Signal code:  (-6)
[runnervmmklqx:04501] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6895845330]
[runnervmmklqx:04501] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f689589eb2c]
[runnervmmklqx:04501] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f689584527e]
[runnervmmklqx:04501] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68958288ff]
[runnervmmklqx:04501] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6895ca5ff5]
[runnervmmklqx:04501] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6895cbb0da]
[runnervmmklqx:04501] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6895ca5a55]
[runnervmmklqx:04501] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6895ca5a6f]
[runnervmmklqx:04501] [ 8] plumed_master(+0x146dd)[0x5589cad086dd]
[runnervmmklqx:04501] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f689582a1ca]
[runnervmmklqx:04501] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f689582a28b]
[runnervmmklqx:04501] [11] plumed_master(+0x15365)[0x5589cad09365]
[runnervmmklqx:04501] *** End of error message ***
</pre>
{% endraw %}
