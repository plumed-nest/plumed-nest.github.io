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
[runnervmi13qx:31763] *** Process received signal ***
[runnervmi13qx:31763] Signal: Aborted (6)
[runnervmi13qx:31763] Signal code:  (-6)
[runnervmi13qx:31763] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd8ebe45330]
[runnervmi13qx:31763] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd8ebe9eb2c]
[runnervmi13qx:31763] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd8ebe4527e]
[runnervmi13qx:31763] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd8ebe288ff]
[runnervmi13qx:31763] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd8ec2a5ff5]
[runnervmi13qx:31763] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd8ec2bb0da]
[runnervmi13qx:31763] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd8ec2a5a55]
[runnervmi13qx:31763] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd8ec2a5a6f]
[runnervmi13qx:31763] [ 8] plumed_master(+0x146dd)[0x560bbede56dd]
[runnervmi13qx:31763] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd8ebe2a1ca]
[runnervmi13qx:31763] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd8ebe2a28b]
[runnervmi13qx:31763] [11] plumed_master(+0x15365)[0x560bbede6365]
[runnervmi13qx:31763] *** End of error message ***
</pre>
{% endraw %}
