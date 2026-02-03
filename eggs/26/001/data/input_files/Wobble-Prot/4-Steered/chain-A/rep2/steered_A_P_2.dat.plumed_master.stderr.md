**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep2/steered_A_P_2.dat   
Download: [zipped raw stdout](steered_A_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04114] *** Process received signal ***
[runnervmkj6or:04114] Signal: Aborted (6)
[runnervmkj6or:04114] Signal code:  (-6)
[runnervmkj6or:04114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67a8445330]
[runnervmkj6or:04114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67a849eb2c]
[runnervmkj6or:04114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67a844527e]
[runnervmkj6or:04114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67a84288ff]
[runnervmkj6or:04114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67a88a5ff5]
[runnervmkj6or:04114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67a88bb0da]
[runnervmkj6or:04114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67a88a5a55]
[runnervmkj6or:04114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67a88a5a6f]
[runnervmkj6or:04114] [ 8] plumed_master(+0x146dd)[0x5615eac586dd]
[runnervmkj6or:04114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67a842a1ca]
[runnervmkj6or:04114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67a842a28b]
[runnervmkj6or:04114] [11] plumed_master(+0x15365)[0x5615eac59365]
[runnervmkj6or:04114] *** End of error message ***
</pre>
{% endraw %}
