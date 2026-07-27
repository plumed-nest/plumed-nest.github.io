**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmvrwv9:04477] *** Process received signal ***
[runnervmvrwv9:04477] Signal: Aborted (6)
[runnervmvrwv9:04477] Signal code:  (-6)
[runnervmvrwv9:04477] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb2b5845330]
[runnervmvrwv9:04477] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb2b589eb2c]
[runnervmvrwv9:04477] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb2b584527e]
[runnervmvrwv9:04477] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb2b58288ff]
[runnervmvrwv9:04477] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb2b5ca5ff5]
[runnervmvrwv9:04477] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb2b5cbb0da]
[runnervmvrwv9:04477] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb2b5ca5a55]
[runnervmvrwv9:04477] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb2b5ca5a6f]
[runnervmvrwv9:04477] [ 8] plumed(+0x146dd)[0x562b0bb4b6dd]
[runnervmvrwv9:04477] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb2b582a1ca]
[runnervmvrwv9:04477] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb2b582a28b]
[runnervmvrwv9:04477] [11] plumed(+0x15365)[0x562b0bb4c365]
[runnervmvrwv9:04477] *** End of error message ***
</pre>
{% endraw %}
