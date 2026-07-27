**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-B/rep1/steered_B_P_1.dat   
Download: [zipped raw stdout](steered_B_P_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_B_P_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Prot/ermsd_ref.pdb
[runnervmvrwv9:04736] *** Process received signal ***
[runnervmvrwv9:04736] Signal: Aborted (6)
[runnervmvrwv9:04736] Signal code:  (-6)
[runnervmvrwv9:04736] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faf68245330]
[runnervmvrwv9:04736] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faf6829eb2c]
[runnervmvrwv9:04736] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faf6824527e]
[runnervmvrwv9:04736] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faf682288ff]
[runnervmvrwv9:04736] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faf686a5ff5]
[runnervmvrwv9:04736] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faf686bb0da]
[runnervmvrwv9:04736] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faf686a5a55]
[runnervmvrwv9:04736] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faf686a5a6f]
[runnervmvrwv9:04736] [ 8] plumed(+0x146dd)[0x55fd871fb6dd]
[runnervmvrwv9:04736] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faf6822a1ca]
[runnervmvrwv9:04736] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faf6822a28b]
[runnervmvrwv9:04736] [11] plumed(+0x15365)[0x55fd871fc365]
[runnervmvrwv9:04736] *** End of error message ***
</pre>
{% endraw %}
