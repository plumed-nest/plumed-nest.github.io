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
[runnervmeorf1:04563] *** Process received signal ***
[runnervmeorf1:04563] Signal: Aborted (6)
[runnervmeorf1:04563] Signal code:  (-6)
[runnervmeorf1:04563] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f818b045330]
[runnervmeorf1:04563] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f818b09eb2c]
[runnervmeorf1:04563] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f818b04527e]
[runnervmeorf1:04563] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f818b0288ff]
[runnervmeorf1:04563] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f818b4a5ff5]
[runnervmeorf1:04563] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f818b4bb0da]
[runnervmeorf1:04563] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f818b4a5a55]
[runnervmeorf1:04563] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f818b4a5a6f]
[runnervmeorf1:04563] [ 8] plumed(+0x146dd)[0x55ad492f46dd]
[runnervmeorf1:04563] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f818b02a1ca]
[runnervmeorf1:04563] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f818b02a28b]
[runnervmeorf1:04563] [11] plumed(+0x15365)[0x55ad492f5365]
[runnervmeorf1:04563] *** End of error message ***
</pre>
{% endraw %}
