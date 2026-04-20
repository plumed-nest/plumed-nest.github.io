**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep2/steered_B_P_2.dat   
Download: [zipped raw stdout](steered_B_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_B_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:04786] *** Process received signal ***
[runnervmeorf1:04786] Signal: Aborted (6)
[runnervmeorf1:04786] Signal code:  (-6)
[runnervmeorf1:04786] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f94eea45330]
[runnervmeorf1:04786] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f94eea9eb2c]
[runnervmeorf1:04786] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f94eea4527e]
[runnervmeorf1:04786] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94eea288ff]
[runnervmeorf1:04786] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94eeea5ff5]
[runnervmeorf1:04786] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94eeebb0da]
[runnervmeorf1:04786] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94eeea5a55]
[runnervmeorf1:04786] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94eeea5a6f]
[runnervmeorf1:04786] [ 8] plumed_master(+0x146dd)[0x55ec71f2e6dd]
[runnervmeorf1:04786] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f94eea2a1ca]
[runnervmeorf1:04786] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f94eea2a28b]
[runnervmeorf1:04786] [11] plumed_master(+0x15365)[0x55ec71f2f365]
[runnervmeorf1:04786] *** End of error message ***
</pre>
{% endraw %}
