**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep2/steered_B_P_2.dat   
Download: [zipped raw stdout](steered_B_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_B_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:04685] *** Process received signal ***
[runnervmvrwv9:04685] Signal: Aborted (6)
[runnervmvrwv9:04685] Signal code:  (-6)
[runnervmvrwv9:04685] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f839f845330]
[runnervmvrwv9:04685] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f839f89eb2c]
[runnervmvrwv9:04685] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f839f84527e]
[runnervmvrwv9:04685] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f839f8288ff]
[runnervmvrwv9:04685] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f839fca5ff5]
[runnervmvrwv9:04685] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f839fcbb0da]
[runnervmvrwv9:04685] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f839fca5a55]
[runnervmvrwv9:04685] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f839fca5a6f]
[runnervmvrwv9:04685] [ 8] plumed(+0x146dd)[0x55d4f27046dd]
[runnervmvrwv9:04685] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f839f82a1ca]
[runnervmvrwv9:04685] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f839f82a28b]
[runnervmvrwv9:04685] [11] plumed(+0x15365)[0x55d4f2705365]
[runnervmvrwv9:04685] *** End of error message ***
</pre>
{% endraw %}
