**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/5-Equil/chain-C/rep2/equil_C_P_2.dat   
Download: [zipped raw stdout](equil_C_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](equil_C_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04697] *** Process received signal ***
[runnervmkj6or:04697] Signal: Aborted (6)
[runnervmkj6or:04697] Signal code:  (-6)
[runnervmkj6or:04697] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc19c45330]
[runnervmkj6or:04697] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc19c9eb2c]
[runnervmkj6or:04697] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc19c4527e]
[runnervmkj6or:04697] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc19c288ff]
[runnervmkj6or:04697] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc1a0a5ff5]
[runnervmkj6or:04697] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc1a0bb0da]
[runnervmkj6or:04697] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc1a0a5a55]
[runnervmkj6or:04697] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc1a0a5a6f]
[runnervmkj6or:04697] [ 8] plumed(+0x146dd)[0x55e6f61e86dd]
[runnervmkj6or:04697] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc19c2a1ca]
[runnervmkj6or:04697] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc19c2a28b]
[runnervmkj6or:04697] [11] plumed(+0x15365)[0x55e6f61e9365]
[runnervmkj6or:04697] *** End of error message ***
</pre>
{% endraw %}
