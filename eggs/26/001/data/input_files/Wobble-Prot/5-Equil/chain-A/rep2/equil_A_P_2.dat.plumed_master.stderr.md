**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-A/rep2/equil_A_P_2.dat   
Download: [zipped raw stdout](equil_A_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_A_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04609] *** Process received signal ***
[runnervmkj6or:04609] Signal: Aborted (6)
[runnervmkj6or:04609] Signal code:  (-6)
[runnervmkj6or:04609] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2c16645330]
[runnervmkj6or:04609] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2c1669eb2c]
[runnervmkj6or:04609] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2c1664527e]
[runnervmkj6or:04609] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2c166288ff]
[runnervmkj6or:04609] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2c16aa5ff5]
[runnervmkj6or:04609] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2c16abb0da]
[runnervmkj6or:04609] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2c16aa5a55]
[runnervmkj6or:04609] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2c16aa5a6f]
[runnervmkj6or:04609] [ 8] plumed_master(+0x146dd)[0x55f418fcd6dd]
[runnervmkj6or:04609] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2c1662a1ca]
[runnervmkj6or:04609] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2c1662a28b]
[runnervmkj6or:04609] [11] plumed_master(+0x15365)[0x55f418fce365]
[runnervmkj6or:04609] *** End of error message ***
</pre>
{% endraw %}
