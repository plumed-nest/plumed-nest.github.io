**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-B/rep2/equil_B_P_2.dat   
Download: [zipped raw stdout](equil_B_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_B_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm76f27:05223] *** Process received signal ***
[runnervm76f27:05223] Signal: Aborted (6)
[runnervm76f27:05223] Signal code:  (-6)
[runnervm76f27:05223] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f55f8645330]
[runnervm76f27:05223] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f55f869ec0c]
[runnervm76f27:05223] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f55f864527e]
[runnervm76f27:05223] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55f86288ff]
[runnervm76f27:05223] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55f8aa5ff5]
[runnervm76f27:05223] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55f8abb0da]
[runnervm76f27:05223] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55f8aa5a55]
[runnervm76f27:05223] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55f8aa5a6f]
[runnervm76f27:05223] [ 8] plumed_master(+0x146dd)[0x562d41e1c6dd]
[runnervm76f27:05223] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f55f862a1ca]
[runnervm76f27:05223] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f55f862a28b]
[runnervm76f27:05223] [11] plumed_master(+0x15365)[0x562d41e1d365]
[runnervm76f27:05223] *** End of error message ***
</pre>
{% endraw %}
