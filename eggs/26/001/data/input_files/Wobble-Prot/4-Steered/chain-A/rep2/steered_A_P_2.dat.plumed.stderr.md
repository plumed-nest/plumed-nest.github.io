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
[runnervmmklqx:04198] *** Process received signal ***
[runnervmmklqx:04198] Signal: Aborted (6)
[runnervmmklqx:04198] Signal code:  (-6)
[runnervmmklqx:04198] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd62fa45330]
[runnervmmklqx:04198] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd62fa9eb2c]
[runnervmmklqx:04198] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd62fa4527e]
[runnervmmklqx:04198] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd62fa288ff]
[runnervmmklqx:04198] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd62fea5ff5]
[runnervmmklqx:04198] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd62febb0da]
[runnervmmklqx:04198] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd62fea5a55]
[runnervmmklqx:04198] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd62fea5a6f]
[runnervmmklqx:04198] [ 8] plumed(+0x146dd)[0x56339806b6dd]
[runnervmmklqx:04198] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd62fa2a1ca]
[runnervmmklqx:04198] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd62fa2a28b]
[runnervmmklqx:04198] [11] plumed(+0x15365)[0x56339806c365]
[runnervmmklqx:04198] *** End of error message ***
</pre>
{% endraw %}
