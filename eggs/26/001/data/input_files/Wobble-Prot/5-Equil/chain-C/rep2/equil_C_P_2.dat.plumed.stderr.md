**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/equil_C_P_2.dat   
Download: [zipped raw stdout](equil_C_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_C_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04799] *** Process received signal ***
[runnervmmklqx:04799] Signal: Aborted (6)
[runnervmmklqx:04799] Signal code:  (-6)
[runnervmmklqx:04799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc182045330]
[runnervmmklqx:04799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc18209eb2c]
[runnervmmklqx:04799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc18204527e]
[runnervmmklqx:04799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1820288ff]
[runnervmmklqx:04799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc1824a5ff5]
[runnervmmklqx:04799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc1824bb0da]
[runnervmmklqx:04799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc1824a5a55]
[runnervmmklqx:04799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc1824a5a6f]
[runnervmmklqx:04799] [ 8] plumed(+0x146dd)[0x558aaa9466dd]
[runnervmmklqx:04799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc18202a1ca]
[runnervmmklqx:04799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc18202a28b]
[runnervmmklqx:04799] [11] plumed(+0x15365)[0x558aaa947365]
[runnervmmklqx:04799] *** End of error message ***
</pre>
{% endraw %}
