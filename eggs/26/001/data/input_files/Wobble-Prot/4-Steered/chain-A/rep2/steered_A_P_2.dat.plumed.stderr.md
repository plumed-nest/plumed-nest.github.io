**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-A/rep2/steered_A_P_2.dat   
Download: [zipped raw stdout](steered_A_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervm76f27:04375] *** Process received signal ***
[runnervm76f27:04375] Signal: Aborted (6)
[runnervm76f27:04375] Signal code:  (-6)
[runnervm76f27:04375] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48cd245330]
[runnervm76f27:04375] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48cd29ec0c]
[runnervm76f27:04375] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48cd24527e]
[runnervm76f27:04375] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48cd2288ff]
[runnervm76f27:04375] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48cd6a5ff5]
[runnervm76f27:04375] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48cd6bb0da]
[runnervm76f27:04375] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48cd6a5a55]
[runnervm76f27:04375] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48cd6a5a6f]
[runnervm76f27:04375] [ 8] plumed(+0x146dd)[0x56251a26c6dd]
[runnervm76f27:04375] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48cd22a1ca]
[runnervm76f27:04375] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48cd22a28b]
[runnervm76f27:04375] [11] plumed(+0x15365)[0x56251a26d365]
[runnervm76f27:04375] *** End of error message ***
</pre>
{% endraw %}
