**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep1/steered_A_P_1.dat   
Download: [zipped raw stdout](steered_A_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04183] *** Process received signal ***
[runnervmkj6or:04183] Signal: Aborted (6)
[runnervmkj6or:04183] Signal code:  (-6)
[runnervmkj6or:04183] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7bc8e45330]
[runnervmkj6or:04183] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7bc8e9eb2c]
[runnervmkj6or:04183] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7bc8e4527e]
[runnervmkj6or:04183] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7bc8e288ff]
[runnervmkj6or:04183] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7bc92a5ff5]
[runnervmkj6or:04183] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7bc92bb0da]
[runnervmkj6or:04183] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7bc92a5a55]
[runnervmkj6or:04183] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7bc92a5a6f]
[runnervmkj6or:04183] [ 8] plumed_master(+0x146dd)[0x556648c786dd]
[runnervmkj6or:04183] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7bc8e2a1ca]
[runnervmkj6or:04183] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7bc8e2a28b]
[runnervmkj6or:04183] [11] plumed_master(+0x15365)[0x556648c79365]
[runnervmkj6or:04183] *** End of error message ***
</pre>
{% endraw %}
