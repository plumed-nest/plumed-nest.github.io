**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-A/rep2/equil_A_P_2.dat   
Download: [zipped raw stdout](equil_A_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_A_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmi13qx:32109] *** Process received signal ***
[runnervmi13qx:32109] Signal: Aborted (6)
[runnervmi13qx:32109] Signal code:  (-6)
[runnervmi13qx:32109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f02a3445330]
[runnervmi13qx:32109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f02a349eb2c]
[runnervmi13qx:32109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f02a344527e]
[runnervmi13qx:32109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02a34288ff]
[runnervmi13qx:32109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02a38a5ff5]
[runnervmi13qx:32109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02a38bb0da]
[runnervmi13qx:32109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02a38a5a55]
[runnervmi13qx:32109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02a38a5a6f]
[runnervmi13qx:32109] [ 8] plumed(+0x146dd)[0x55fda148d6dd]
[runnervmi13qx:32109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f02a342a1ca]
[runnervmi13qx:32109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f02a342a28b]
[runnervmi13qx:32109] [11] plumed(+0x15365)[0x55fda148e365]
[runnervmi13qx:32109] *** End of error message ***
</pre>
{% endraw %}
