**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-B/rep1/equil_B_P_1.dat   
Download: [zipped raw stdout](equil_B_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_B_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm76f27:05275] *** Process received signal ***
[runnervm76f27:05275] Signal: Aborted (6)
[runnervm76f27:05275] Signal code:  (-6)
[runnervm76f27:05275] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48a0245330]
[runnervm76f27:05275] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48a029ec0c]
[runnervm76f27:05275] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48a024527e]
[runnervm76f27:05275] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48a02288ff]
[runnervm76f27:05275] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48a06a5ff5]
[runnervm76f27:05275] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48a06bb0da]
[runnervm76f27:05275] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48a06a5a55]
[runnervm76f27:05275] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48a06a5a6f]
[runnervm76f27:05275] [ 8] plumed_master(+0x146dd)[0x55baf632c6dd]
[runnervm76f27:05275] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48a022a1ca]
[runnervm76f27:05275] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48a022a28b]
[runnervm76f27:05275] [11] plumed_master(+0x15365)[0x55baf632d365]
[runnervm76f27:05275] *** End of error message ***
</pre>
{% endraw %}
