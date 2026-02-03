**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-A/rep2/equil_A_P_2.dat   
Download: [zipped raw stdout](equil_A_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_A_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04593] *** Process received signal ***
[runnervmkj6or:04593] Signal: Aborted (6)
[runnervmkj6or:04593] Signal code:  (-6)
[runnervmkj6or:04593] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f33b6445330]
[runnervmkj6or:04593] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f33b649eb2c]
[runnervmkj6or:04593] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f33b644527e]
[runnervmkj6or:04593] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33b64288ff]
[runnervmkj6or:04593] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33b68a5ff5]
[runnervmkj6or:04593] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33b68bb0da]
[runnervmkj6or:04593] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33b68a5a55]
[runnervmkj6or:04593] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33b68a5a6f]
[runnervmkj6or:04593] [ 8] plumed(+0x146dd)[0x558514d706dd]
[runnervmkj6or:04593] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f33b642a1ca]
[runnervmkj6or:04593] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f33b642a28b]
[runnervmkj6or:04593] [11] plumed(+0x15365)[0x558514d71365]
[runnervmkj6or:04593] *** End of error message ***
</pre>
{% endraw %}
