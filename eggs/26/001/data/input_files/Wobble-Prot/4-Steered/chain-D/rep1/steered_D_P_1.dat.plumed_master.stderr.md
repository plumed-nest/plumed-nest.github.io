**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep1/steered_D_P_1.dat   
Download: [zipped raw stdout](steered_D_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_D_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04451] *** Process received signal ***
[runnervmkj6or:04451] Signal: Aborted (6)
[runnervmkj6or:04451] Signal code:  (-6)
[runnervmkj6or:04451] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbdcb045330]
[runnervmkj6or:04451] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbdcb09eb2c]
[runnervmkj6or:04451] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbdcb04527e]
[runnervmkj6or:04451] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbdcb0288ff]
[runnervmkj6or:04451] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbdcb4a5ff5]
[runnervmkj6or:04451] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbdcb4bb0da]
[runnervmkj6or:04451] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbdcb4a5a55]
[runnervmkj6or:04451] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbdcb4a5a6f]
[runnervmkj6or:04451] [ 8] plumed_master(+0x146dd)[0x55cf9063a6dd]
[runnervmkj6or:04451] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbdcb02a1ca]
[runnervmkj6or:04451] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbdcb02a28b]
[runnervmkj6or:04451] [11] plumed_master(+0x15365)[0x55cf9063b365]
[runnervmkj6or:04451] *** End of error message ***
</pre>
{% endraw %}
