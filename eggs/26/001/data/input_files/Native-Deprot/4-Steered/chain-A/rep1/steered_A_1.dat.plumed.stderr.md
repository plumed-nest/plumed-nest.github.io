**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Native-Deprot/4-Steered/chain-A/rep1/steered_A_1.dat   
Download: [zipped raw stdout](steered_A_1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](steered_A_1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ERMSD with label ermsd : missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/ermsd_ref.pdb
[runnervmi13qx:32625] *** Process received signal ***
[runnervmi13qx:32625] Signal: Aborted (6)
[runnervmi13qx:32625] Signal code:  (-6)
[runnervmi13qx:32625] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf83e45330]
[runnervmi13qx:32625] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf83e9eb2c]
[runnervmi13qx:32625] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf83e4527e]
[runnervmi13qx:32625] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf83e288ff]
[runnervmi13qx:32625] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf842a5ff5]
[runnervmi13qx:32625] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf842bb0da]
[runnervmi13qx:32625] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf842a5a55]
[runnervmi13qx:32625] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf842a5a6f]
[runnervmi13qx:32625] [ 8] plumed(+0x146dd)[0x564c7020f6dd]
[runnervmi13qx:32625] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf83e2a1ca]
[runnervmi13qx:32625] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf83e2a28b]
[runnervmi13qx:32625] [11] plumed(+0x15365)[0x564c70210365]
[runnervmi13qx:32625] *** End of error message ***
</pre>
{% endraw %}
