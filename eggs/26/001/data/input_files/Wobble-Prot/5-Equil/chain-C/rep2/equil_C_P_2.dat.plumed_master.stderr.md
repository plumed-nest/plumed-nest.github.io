**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/equil_C_P_2.dat   
Download: [zipped raw stdout](equil_C_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_C_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm76f27:04965] *** Process received signal ***
[runnervm76f27:04965] Signal: Aborted (6)
[runnervm76f27:04965] Signal code:  (-6)
[runnervm76f27:04965] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa289e45330]
[runnervm76f27:04965] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa289e9ec0c]
[runnervm76f27:04965] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa289e4527e]
[runnervm76f27:04965] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa289e288ff]
[runnervm76f27:04965] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa28a2a5ff5]
[runnervm76f27:04965] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa28a2bb0da]
[runnervm76f27:04965] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa28a2a5a55]
[runnervm76f27:04965] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa28a2a5a6f]
[runnervm76f27:04965] [ 8] plumed_master(+0x146dd)[0x564bc9f356dd]
[runnervm76f27:04965] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa289e2a1ca]
[runnervm76f27:04965] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa289e2a28b]
[runnervm76f27:04965] [11] plumed_master(+0x15365)[0x564bc9f36365]
[runnervm76f27:04965] *** End of error message ***
</pre>
{% endraw %}
