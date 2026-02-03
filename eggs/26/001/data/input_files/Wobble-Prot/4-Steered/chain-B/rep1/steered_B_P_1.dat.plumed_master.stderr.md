**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep1/steered_B_P_1.dat   
Download: [zipped raw stdout](steered_B_P_1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_B_P_1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmkj6or:04556] *** Process received signal ***
[runnervmkj6or:04556] Signal: Aborted (6)
[runnervmkj6or:04556] Signal code:  (-6)
[runnervmkj6or:04556] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb822245330]
[runnervmkj6or:04556] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb82229eb2c]
[runnervmkj6or:04556] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb82224527e]
[runnervmkj6or:04556] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8222288ff]
[runnervmkj6or:04556] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8226a5ff5]
[runnervmkj6or:04556] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8226bb0da]
[runnervmkj6or:04556] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8226a5a55]
[runnervmkj6or:04556] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8226a5a6f]
[runnervmkj6or:04556] [ 8] plumed_master(+0x146dd)[0x55aaf363a6dd]
[runnervmkj6or:04556] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb82222a1ca]
[runnervmkj6or:04556] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb82222a28b]
[runnervmkj6or:04556] [11] plumed_master(+0x15365)[0x55aaf363b365]
[runnervmkj6or:04556] *** End of error message ***
</pre>
{% endraw %}
