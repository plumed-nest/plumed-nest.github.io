**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep1/steered_B_P_1.dat   
Download: [zipped raw stdout](steered_B_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_B_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmgx7h7:04399] *** Process received signal ***
[runnervmgx7h7:04399] Signal: Aborted (6)
[runnervmgx7h7:04399] Signal code:  (-6)
[runnervmgx7h7:04399] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe4a2a45330]
[runnervmgx7h7:04399] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe4a2a9ec0c]
[runnervmgx7h7:04399] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe4a2a4527e]
[runnervmgx7h7:04399] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4a2a288ff]
[runnervmgx7h7:04399] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4a2ea5ff5]
[runnervmgx7h7:04399] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4a2ebb0da]
[runnervmgx7h7:04399] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4a2ea5a55]
[runnervmgx7h7:04399] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4a2ea5a6f]
[runnervmgx7h7:04399] [ 8] plumed(+0x146dd)[0x5648a86fd6dd]
[runnervmgx7h7:04399] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe4a2a2a1ca]
[runnervmgx7h7:04399] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe4a2a2a28b]
[runnervmgx7h7:04399] [11] plumed(+0x15365)[0x5648a86fe365]
[runnervmgx7h7:04399] *** End of error message ***
</pre>
{% endraw %}
