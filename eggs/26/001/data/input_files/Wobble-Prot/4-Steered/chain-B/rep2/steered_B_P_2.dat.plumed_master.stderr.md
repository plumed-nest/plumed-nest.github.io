**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep2/steered_B_P_2.dat   
Download: [zipped raw stdout](steered_B_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_B_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:04701] *** Process received signal ***
[runnervmvrwv9:04701] Signal: Aborted (6)
[runnervmvrwv9:04701] Signal code:  (-6)
[runnervmvrwv9:04701] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1e6b045330]
[runnervmvrwv9:04701] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1e6b09eb2c]
[runnervmvrwv9:04701] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1e6b04527e]
[runnervmvrwv9:04701] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1e6b0288ff]
[runnervmvrwv9:04701] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1e6b4a5ff5]
[runnervmvrwv9:04701] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1e6b4bb0da]
[runnervmvrwv9:04701] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1e6b4a5a55]
[runnervmvrwv9:04701] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1e6b4a5a6f]
[runnervmvrwv9:04701] [ 8] plumed_master(+0x146dd)[0x55c2520ae6dd]
[runnervmvrwv9:04701] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1e6b02a1ca]
[runnervmvrwv9:04701] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1e6b02a28b]
[runnervmvrwv9:04701] [11] plumed_master(+0x15365)[0x55c2520af365]
[runnervmvrwv9:04701] *** End of error message ***
</pre>
{% endraw %}
