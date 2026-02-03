**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep1/steered_C_P_1.dat   
Download: [zipped raw stdout](steered_C_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_C_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04329] *** Process received signal ***
[runnervmkj6or:04329] Signal: Aborted (6)
[runnervmkj6or:04329] Signal code:  (-6)
[runnervmkj6or:04329] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6558c45330]
[runnervmkj6or:04329] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6558c9eb2c]
[runnervmkj6or:04329] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6558c4527e]
[runnervmkj6or:04329] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6558c288ff]
[runnervmkj6or:04329] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65590a5ff5]
[runnervmkj6or:04329] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65590bb0da]
[runnervmkj6or:04329] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65590a5a55]
[runnervmkj6or:04329] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65590a5a6f]
[runnervmkj6or:04329] [ 8] plumed(+0x146dd)[0x55768a15c6dd]
[runnervmkj6or:04329] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6558c2a1ca]
[runnervmkj6or:04329] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6558c2a28b]
[runnervmkj6or:04329] [11] plumed(+0x15365)[0x55768a15d365]
[runnervmkj6or:04329] *** End of error message ***
</pre>
{% endraw %}
