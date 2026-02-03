**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-B/rep1/equil_B_P_1.dat   
Download: [zipped raw stdout](equil_B_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](equil_B_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:05027] *** Process received signal ***
[runnervmkj6or:05027] Signal: Aborted (6)
[runnervmkj6or:05027] Signal code:  (-6)
[runnervmkj6or:05027] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f11e4445330]
[runnervmkj6or:05027] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f11e449eb2c]
[runnervmkj6or:05027] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f11e444527e]
[runnervmkj6or:05027] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f11e44288ff]
[runnervmkj6or:05027] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f11e48a5ff5]
[runnervmkj6or:05027] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f11e48bb0da]
[runnervmkj6or:05027] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f11e48a5a55]
[runnervmkj6or:05027] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f11e48a5a6f]
[runnervmkj6or:05027] [ 8] plumed_master(+0x146dd)[0x55dad8e686dd]
[runnervmkj6or:05027] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f11e442a1ca]
[runnervmkj6or:05027] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f11e442a28b]
[runnervmkj6or:05027] [11] plumed_master(+0x15365)[0x55dad8e69365]
[runnervmkj6or:05027] *** End of error message ***
</pre>
{% endraw %}
