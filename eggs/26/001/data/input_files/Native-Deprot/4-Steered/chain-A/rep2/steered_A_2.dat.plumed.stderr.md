**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep2/steered_A_2.dat   
Download: [zipped raw stdout](steered_A_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmeorf1:05337] *** Process received signal ***
[runnervmeorf1:05337] Signal: Aborted (6)
[runnervmeorf1:05337] Signal code:  (-6)
[runnervmeorf1:05337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f46ef445330]
[runnervmeorf1:05337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f46ef49eb2c]
[runnervmeorf1:05337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f46ef44527e]
[runnervmeorf1:05337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46ef4288ff]
[runnervmeorf1:05337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46ef8a5ff5]
[runnervmeorf1:05337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46ef8bb0da]
[runnervmeorf1:05337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46ef8a5a55]
[runnervmeorf1:05337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46ef8a5a6f]
[runnervmeorf1:05337] [ 8] plumed(+0x146dd)[0x564977afc6dd]
[runnervmeorf1:05337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f46ef42a1ca]
[runnervmeorf1:05337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f46ef42a28b]
[runnervmeorf1:05337] [11] plumed(+0x15365)[0x564977afd365]
[runnervmeorf1:05337] *** End of error message ***
</pre>
{% endraw %}
