**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep1/steered_A_1.dat   
Download: [zipped raw stdout](steered_A_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmeorf1:05405] *** Process received signal ***
[runnervmeorf1:05405] Signal: Aborted (6)
[runnervmeorf1:05405] Signal code:  (-6)
[runnervmeorf1:05405] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f630d645330]
[runnervmeorf1:05405] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f630d69eb2c]
[runnervmeorf1:05405] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f630d64527e]
[runnervmeorf1:05405] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f630d6288ff]
[runnervmeorf1:05405] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f630daa5ff5]
[runnervmeorf1:05405] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f630dabb0da]
[runnervmeorf1:05405] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f630daa5a55]
[runnervmeorf1:05405] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f630daa5a6f]
[runnervmeorf1:05405] [ 8] plumed_master(+0x146dd)[0x5577715ea6dd]
[runnervmeorf1:05405] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f630d62a1ca]
[runnervmeorf1:05405] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f630d62a28b]
[runnervmeorf1:05405] [11] plumed_master(+0x15365)[0x5577715eb365]
[runnervmeorf1:05405] *** End of error message ***
</pre>
{% endraw %}
