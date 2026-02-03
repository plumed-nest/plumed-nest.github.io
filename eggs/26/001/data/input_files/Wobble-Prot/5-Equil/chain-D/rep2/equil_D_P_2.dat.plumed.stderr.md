**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-D/rep2/equil_D_P_2.dat   
Download: [zipped raw stdout](equil_D_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_D_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04852] *** Process received signal ***
[runnervmkj6or:04852] Signal: Aborted (6)
[runnervmkj6or:04852] Signal code:  (-6)
[runnervmkj6or:04852] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff558a45330]
[runnervmkj6or:04852] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff558a9eb2c]
[runnervmkj6or:04852] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff558a4527e]
[runnervmkj6or:04852] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff558a288ff]
[runnervmkj6or:04852] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff558ea5ff5]
[runnervmkj6or:04852] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff558ebb0da]
[runnervmkj6or:04852] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff558ea5a55]
[runnervmkj6or:04852] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff558ea5a6f]
[runnervmkj6or:04852] [ 8] plumed(+0x146dd)[0x561215e066dd]
[runnervmkj6or:04852] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff558a2a1ca]
[runnervmkj6or:04852] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff558a2a28b]
[runnervmkj6or:04852] [11] plumed(+0x15365)[0x561215e07365]
[runnervmkj6or:04852] *** End of error message ***
</pre>
{% endraw %}
