**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep1/steered_D_P_1.dat   
Download: [zipped raw stdout](steered_D_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_D_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmi13qx:31970] *** Process received signal ***
[runnervmi13qx:31970] Signal: Aborted (6)
[runnervmi13qx:31970] Signal code:  (-6)
[runnervmi13qx:31970] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff103445330]
[runnervmi13qx:31970] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff10349eb2c]
[runnervmi13qx:31970] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff10344527e]
[runnervmi13qx:31970] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1034288ff]
[runnervmi13qx:31970] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1038a5ff5]
[runnervmi13qx:31970] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1038bb0da]
[runnervmi13qx:31970] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1038a5a55]
[runnervmi13qx:31970] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1038a5a6f]
[runnervmi13qx:31970] [ 8] plumed_master(+0x146dd)[0x55c45ae7a6dd]
[runnervmi13qx:31970] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff10342a1ca]
[runnervmi13qx:31970] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff10342a28b]
[runnervmi13qx:31970] [11] plumed_master(+0x15365)[0x55c45ae7b365]
[runnervmi13qx:31970] *** End of error message ***
</pre>
{% endraw %}
