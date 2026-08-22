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
[runnervm76f27:04654] *** Process received signal ***
[runnervm76f27:04654] Signal: Aborted (6)
[runnervm76f27:04654] Signal code:  (-6)
[runnervm76f27:04654] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4053e45330]
[runnervm76f27:04654] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4053e9ec0c]
[runnervm76f27:04654] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4053e4527e]
[runnervm76f27:04654] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4053e288ff]
[runnervm76f27:04654] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f40542a5ff5]
[runnervm76f27:04654] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f40542bb0da]
[runnervm76f27:04654] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f40542a5a55]
[runnervm76f27:04654] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f40542a5a6f]
[runnervm76f27:04654] [ 8] plumed_master(+0x146dd)[0x55a39b4216dd]
[runnervm76f27:04654] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4053e2a1ca]
[runnervm76f27:04654] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4053e2a28b]
[runnervm76f27:04654] [11] plumed_master(+0x15365)[0x55a39b422365]
[runnervm76f27:04654] *** End of error message ***
</pre>
{% endraw %}
