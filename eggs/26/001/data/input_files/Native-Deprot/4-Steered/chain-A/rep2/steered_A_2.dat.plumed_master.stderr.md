**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep2/steered_A_2.dat   
Download: [zipped raw stdout](steered_A_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmvrwv9:05270] *** Process received signal ***
[runnervmvrwv9:05270] Signal: Aborted (6)
[runnervmvrwv9:05270] Signal code:  (-6)
[runnervmvrwv9:05270] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb086845330]
[runnervmvrwv9:05270] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb08689eb2c]
[runnervmvrwv9:05270] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb08684527e]
[runnervmvrwv9:05270] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0868288ff]
[runnervmvrwv9:05270] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb086ca5ff5]
[runnervmvrwv9:05270] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb086cbb0da]
[runnervmvrwv9:05270] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb086ca5a55]
[runnervmvrwv9:05270] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb086ca5a6f]
[runnervmvrwv9:05270] [ 8] plumed_master(+0x146dd)[0x55ac28dea6dd]
[runnervmvrwv9:05270] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb08682a1ca]
[runnervmvrwv9:05270] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb08682a28b]
[runnervmvrwv9:05270] [11] plumed_master(+0x15365)[0x55ac28deb365]
[runnervmvrwv9:05270] *** End of error message ***
</pre>
{% endraw %}
