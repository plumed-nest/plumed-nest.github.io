**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep2/steered_A_2.dat   
Download: [zipped raw stdout](steered_A_2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](steered_A_2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmi13qx:32589] *** Process received signal ***
[runnervmi13qx:32589] Signal: Aborted (6)
[runnervmi13qx:32589] Signal code:  (-6)
[runnervmi13qx:32589] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0b15045330]
[runnervmi13qx:32589] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0b1509eb2c]
[runnervmi13qx:32589] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0b1504527e]
[runnervmi13qx:32589] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0b150288ff]
[runnervmi13qx:32589] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0b154a5ff5]
[runnervmi13qx:32589] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0b154bb0da]
[runnervmi13qx:32589] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0b154a5a55]
[runnervmi13qx:32589] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0b154a5a6f]
[runnervmi13qx:32589] [ 8] plumed_master(+0x146dd)[0x55ed407236dd]
[runnervmi13qx:32589] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0b1502a1ca]
[runnervmi13qx:32589] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0b1502a28b]
[runnervmi13qx:32589] [11] plumed_master(+0x15365)[0x55ed40724365]
[runnervmi13qx:32589] *** End of error message ***
</pre>
{% endraw %}
