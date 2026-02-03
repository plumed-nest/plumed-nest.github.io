**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-D/rep1/equil_D_P_1.dat   
Download: [zipped raw stdout](equil_D_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_D_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04924] *** Process received signal ***
[runnervmkj6or:04924] Signal: Aborted (6)
[runnervmkj6or:04924] Signal code:  (-6)
[runnervmkj6or:04924] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7acf645330]
[runnervmkj6or:04924] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7acf69eb2c]
[runnervmkj6or:04924] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7acf64527e]
[runnervmkj6or:04924] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7acf6288ff]
[runnervmkj6or:04924] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7acfaa5ff5]
[runnervmkj6or:04924] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7acfabb0da]
[runnervmkj6or:04924] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7acfaa5a55]
[runnervmkj6or:04924] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7acfaa5a6f]
[runnervmkj6or:04924] [ 8] plumed_master(+0x146dd)[0x56183e0f56dd]
[runnervmkj6or:04924] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7acf62a1ca]
[runnervmkj6or:04924] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7acf62a28b]
[runnervmkj6or:04924] [11] plumed_master(+0x15365)[0x56183e0f6365]
[runnervmkj6or:04924] *** End of error message ***
</pre>
{% endraw %}
