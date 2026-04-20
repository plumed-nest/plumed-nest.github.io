**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/steered_C_P_2.dat   
Download: [zipped raw stdout](steered_C_P_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_C_P_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmeorf1:04528] *** Process received signal ***
[runnervmeorf1:04528] Signal: Aborted (6)
[runnervmeorf1:04528] Signal code:  (-6)
[runnervmeorf1:04528] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5fba645330]
[runnervmeorf1:04528] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5fba69eb2c]
[runnervmeorf1:04528] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5fba64527e]
[runnervmeorf1:04528] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5fba6288ff]
[runnervmeorf1:04528] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5fbaaa5ff5]
[runnervmeorf1:04528] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5fbaabb0da]
[runnervmeorf1:04528] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5fbaaa5a55]
[runnervmeorf1:04528] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5fbaaa5a6f]
[runnervmeorf1:04528] [ 8] plumed_master(+0x146dd)[0x55f5ffcd36dd]
[runnervmeorf1:04528] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5fba62a1ca]
[runnervmeorf1:04528] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5fba62a28b]
[runnervmeorf1:04528] [11] plumed_master(+0x15365)[0x55f5ffcd4365]
[runnervmeorf1:04528] *** End of error message ***
</pre>
{% endraw %}
