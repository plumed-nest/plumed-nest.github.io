**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-B/rep2/equil_B_P_2.dat   
Download: [zipped raw stdout](equil_B_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_B_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmi13qx:32471] *** Process received signal ***
[runnervmi13qx:32471] Signal: Aborted (6)
[runnervmi13qx:32471] Signal code:  (-6)
[runnervmi13qx:32471] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f94e3e45330]
[runnervmi13qx:32471] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f94e3e9eb2c]
[runnervmi13qx:32471] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f94e3e4527e]
[runnervmi13qx:32471] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94e3e288ff]
[runnervmi13qx:32471] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94e42a5ff5]
[runnervmi13qx:32471] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94e42bb0da]
[runnervmi13qx:32471] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94e42a5a55]
[runnervmi13qx:32471] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94e42a5a6f]
[runnervmi13qx:32471] [ 8] plumed(+0x146dd)[0x557cb47f06dd]
[runnervmi13qx:32471] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f94e3e2a1ca]
[runnervmi13qx:32471] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f94e3e2a28b]
[runnervmi13qx:32471] [11] plumed(+0x15365)[0x557cb47f1365]
[runnervmi13qx:32471] *** End of error message ***
</pre>
{% endraw %}
