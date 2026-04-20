**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep1/steered_B_P_1.dat   
Download: [zipped raw stdout](steered_B_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_B_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:04821] *** Process received signal ***
[runnervmeorf1:04821] Signal: Aborted (6)
[runnervmeorf1:04821] Signal code:  (-6)
[runnervmeorf1:04821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0ba4a45330]
[runnervmeorf1:04821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0ba4a9eb2c]
[runnervmeorf1:04821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0ba4a4527e]
[runnervmeorf1:04821] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0ba4a288ff]
[runnervmeorf1:04821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0ba4ea5ff5]
[runnervmeorf1:04821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0ba4ebb0da]
[runnervmeorf1:04821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0ba4ea5a55]
[runnervmeorf1:04821] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0ba4ea5a6f]
[runnervmeorf1:04821] [ 8] plumed(+0x146dd)[0x559747cce6dd]
[runnervmeorf1:04821] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0ba4a2a1ca]
[runnervmeorf1:04821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0ba4a2a28b]
[runnervmeorf1:04821] [11] plumed(+0x15365)[0x559747ccf365]
[runnervmeorf1:04821] *** End of error message ***
</pre>
{% endraw %}
