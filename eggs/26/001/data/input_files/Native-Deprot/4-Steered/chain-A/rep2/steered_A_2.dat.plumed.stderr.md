**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep2/steered_A_2.dat   
Download: [zipped raw stdout](steered_A_2.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_2.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmmklqx:05161] *** Process received signal ***
[runnervmmklqx:05161] Signal: Aborted (6)
[runnervmmklqx:05161] Signal code:  (-6)
[runnervmmklqx:05161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2979045330]
[runnervmmklqx:05161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f297909eb2c]
[runnervmmklqx:05161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f297904527e]
[runnervmmklqx:05161] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29790288ff]
[runnervmmklqx:05161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29794a5ff5]
[runnervmmklqx:05161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29794bb0da]
[runnervmmklqx:05161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29794a5a55]
[runnervmmklqx:05161] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29794a5a6f]
[runnervmmklqx:05161] [ 8] plumed(+0x146dd)[0x55bec6a5d6dd]
[runnervmmklqx:05161] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f297902a1ca]
[runnervmmklqx:05161] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f297902a28b]
[runnervmmklqx:05161] [11] plumed(+0x15365)[0x55bec6a5e365]
[runnervmmklqx:05161] *** End of error message ***
</pre>
{% endraw %}
