**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep2/steered_A_P_2.dat   
Download: [zipped raw stdout](steered_A_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04099] *** Process received signal ***
[runnervmkj6or:04099] Signal: Aborted (6)
[runnervmkj6or:04099] Signal code:  (-6)
[runnervmkj6or:04099] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0e33045330]
[runnervmkj6or:04099] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0e3309eb2c]
[runnervmkj6or:04099] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0e3304527e]
[runnervmkj6or:04099] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0e330288ff]
[runnervmkj6or:04099] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0e334a5ff5]
[runnervmkj6or:04099] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0e334bb0da]
[runnervmkj6or:04099] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0e334a5a55]
[runnervmkj6or:04099] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0e334a5a6f]
[runnervmkj6or:04099] [ 8] plumed(+0x146dd)[0x55c6c9a7a6dd]
[runnervmkj6or:04099] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0e3302a1ca]
[runnervmkj6or:04099] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0e3302a28b]
[runnervmkj6or:04099] [11] plumed(+0x15365)[0x55c6c9a7b365]
[runnervmkj6or:04099] *** End of error message ***
</pre>
{% endraw %}
