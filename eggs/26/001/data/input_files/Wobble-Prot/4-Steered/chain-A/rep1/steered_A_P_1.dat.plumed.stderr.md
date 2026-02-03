**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep1/steered_A_P_1.dat   
Download: [zipped raw stdout](steered_A_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04167] *** Process received signal ***
[runnervmkj6or:04167] Signal: Aborted (6)
[runnervmkj6or:04167] Signal code:  (-6)
[runnervmkj6or:04167] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe261045330]
[runnervmkj6or:04167] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe26109eb2c]
[runnervmkj6or:04167] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe26104527e]
[runnervmkj6or:04167] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe2610288ff]
[runnervmkj6or:04167] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe2614a5ff5]
[runnervmkj6or:04167] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe2614bb0da]
[runnervmkj6or:04167] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe2614a5a55]
[runnervmkj6or:04167] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe2614a5a6f]
[runnervmkj6or:04167] [ 8] plumed(+0x146dd)[0x55fb86b436dd]
[runnervmkj6or:04167] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe26102a1ca]
[runnervmkj6or:04167] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe26102a28b]
[runnervmkj6or:04167] [11] plumed(+0x15365)[0x55fb86b44365]
[runnervmkj6or:04167] *** End of error message ***
</pre>
{% endraw %}
