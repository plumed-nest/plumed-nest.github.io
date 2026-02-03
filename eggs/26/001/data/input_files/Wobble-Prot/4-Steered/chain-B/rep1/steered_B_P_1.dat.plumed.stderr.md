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
[runnervmkj6or:04541] *** Process received signal ***
[runnervmkj6or:04541] Signal: Aborted (6)
[runnervmkj6or:04541] Signal code:  (-6)
[runnervmkj6or:04541] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f39fc245330]
[runnervmkj6or:04541] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f39fc29eb2c]
[runnervmkj6or:04541] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f39fc24527e]
[runnervmkj6or:04541] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39fc2288ff]
[runnervmkj6or:04541] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f39fc6a5ff5]
[runnervmkj6or:04541] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f39fc6bb0da]
[runnervmkj6or:04541] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f39fc6a5a55]
[runnervmkj6or:04541] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f39fc6a5a6f]
[runnervmkj6or:04541] [ 8] plumed(+0x146dd)[0x55d6ead366dd]
[runnervmkj6or:04541] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f39fc22a1ca]
[runnervmkj6or:04541] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f39fc22a28b]
[runnervmkj6or:04541] [11] plumed(+0x15365)[0x55d6ead37365]
[runnervmkj6or:04541] *** End of error message ***
</pre>
{% endraw %}
