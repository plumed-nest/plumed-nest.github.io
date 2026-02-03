**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep2/steered_D_P_2.dat   
Download: [zipped raw stdout](steered_D_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_D_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04397] *** Process received signal ***
[runnervmkj6or:04397] Signal: Aborted (6)
[runnervmkj6or:04397] Signal code:  (-6)
[runnervmkj6or:04397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2d5e645330]
[runnervmkj6or:04397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2d5e69eb2c]
[runnervmkj6or:04397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2d5e64527e]
[runnervmkj6or:04397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2d5e6288ff]
[runnervmkj6or:04397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2d5eaa5ff5]
[runnervmkj6or:04397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2d5eabb0da]
[runnervmkj6or:04397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2d5eaa5a55]
[runnervmkj6or:04397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2d5eaa5a6f]
[runnervmkj6or:04397] [ 8] plumed_master(+0x146dd)[0x55d8040276dd]
[runnervmkj6or:04397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2d5e62a1ca]
[runnervmkj6or:04397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2d5e62a28b]
[runnervmkj6or:04397] [11] plumed_master(+0x15365)[0x55d804028365]
[runnervmkj6or:04397] *** End of error message ***
</pre>
{% endraw %}
