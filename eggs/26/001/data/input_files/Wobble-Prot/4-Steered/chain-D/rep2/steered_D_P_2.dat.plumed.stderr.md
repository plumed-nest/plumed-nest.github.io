**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep2/steered_D_P_2.dat   
Download: [zipped raw stdout](steered_D_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_D_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04382] *** Process received signal ***
[runnervmkj6or:04382] Signal: Aborted (6)
[runnervmkj6or:04382] Signal code:  (-6)
[runnervmkj6or:04382] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc9e245330]
[runnervmkj6or:04382] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc9e29eb2c]
[runnervmkj6or:04382] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc9e24527e]
[runnervmkj6or:04382] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc9e2288ff]
[runnervmkj6or:04382] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc9e6a5ff5]
[runnervmkj6or:04382] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc9e6bb0da]
[runnervmkj6or:04382] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc9e6a5a55]
[runnervmkj6or:04382] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc9e6a5a6f]
[runnervmkj6or:04382] [ 8] plumed(+0x146dd)[0x55d9158d86dd]
[runnervmkj6or:04382] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc9e22a1ca]
[runnervmkj6or:04382] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc9e22a28b]
[runnervmkj6or:04382] [11] plumed(+0x15365)[0x55d9158d9365]
[runnervmkj6or:04382] *** End of error message ***
</pre>
{% endraw %}
