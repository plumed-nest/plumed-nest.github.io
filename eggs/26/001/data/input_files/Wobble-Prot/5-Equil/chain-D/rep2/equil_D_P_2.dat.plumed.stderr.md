**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-D/rep2/equil_D_P_2.dat   
Download: [zipped raw stdout](equil_D_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_D_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmmklqx:04955] *** Process received signal ***
[runnervmmklqx:04955] Signal: Aborted (6)
[runnervmmklqx:04955] Signal code:  (-6)
[runnervmmklqx:04955] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f80b7445330]
[runnervmmklqx:04955] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f80b749eb2c]
[runnervmmklqx:04955] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f80b744527e]
[runnervmmklqx:04955] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80b74288ff]
[runnervmmklqx:04955] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80b78a5ff5]
[runnervmmklqx:04955] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80b78bb0da]
[runnervmmklqx:04955] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80b78a5a55]
[runnervmmklqx:04955] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80b78a5a6f]
[runnervmmklqx:04955] [ 8] plumed(+0x146dd)[0x5616e0c606dd]
[runnervmmklqx:04955] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f80b742a1ca]
[runnervmmklqx:04955] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f80b742a28b]
[runnervmmklqx:04955] [11] plumed(+0x15365)[0x5616e0c61365]
[runnervmmklqx:04955] *** End of error message ***
</pre>
{% endraw %}
