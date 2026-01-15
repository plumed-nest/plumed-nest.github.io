**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmi13qx:31798] *** Process received signal ***
[runnervmi13qx:31798] Signal: Aborted (6)
[runnervmi13qx:31798] Signal code:  (-6)
[runnervmi13qx:31798] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff07b045330]
[runnervmi13qx:31798] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff07b09eb2c]
[runnervmi13qx:31798] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff07b04527e]
[runnervmi13qx:31798] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff07b0288ff]
[runnervmi13qx:31798] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff07b4a5ff5]
[runnervmi13qx:31798] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff07b4bb0da]
[runnervmi13qx:31798] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff07b4a5a55]
[runnervmi13qx:31798] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff07b4a5a6f]
[runnervmi13qx:31798] [ 8] plumed(+0x146dd)[0x560d720aa6dd]
[runnervmi13qx:31798] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff07b02a1ca]
[runnervmi13qx:31798] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff07b02a28b]
[runnervmi13qx:31798] [11] plumed(+0x15365)[0x560d720ab365]
[runnervmi13qx:31798] *** End of error message ***
</pre>
{% endraw %}
