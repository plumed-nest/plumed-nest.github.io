**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-D/rep2/steered_D_P_2.dat   
Download: [zipped raw stdout](steered_D_P_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_D_P_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:04580] *** Process received signal ***
[runnervmvrwv9:04580] Signal: Aborted (6)
[runnervmvrwv9:04580] Signal code:  (-6)
[runnervmvrwv9:04580] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fefaec45330]
[runnervmvrwv9:04580] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fefaec9eb2c]
[runnervmvrwv9:04580] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fefaec4527e]
[runnervmvrwv9:04580] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fefaec288ff]
[runnervmvrwv9:04580] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fefaf0a5ff5]
[runnervmvrwv9:04580] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fefaf0bb0da]
[runnervmvrwv9:04580] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fefaf0a5a55]
[runnervmvrwv9:04580] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fefaf0a5a6f]
[runnervmvrwv9:04580] [ 8] plumed(+0x146dd)[0x5625eb0fc6dd]
[runnervmvrwv9:04580] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fefaec2a1ca]
[runnervmvrwv9:04580] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fefaec2a28b]
[runnervmvrwv9:04580] [11] plumed(+0x15365)[0x5625eb0fd365]
[runnervmvrwv9:04580] *** End of error message ***
</pre>
{% endraw %}
