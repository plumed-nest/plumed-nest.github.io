**Project ID:** [plumID:26.001]({{ '/' | absolute_url }}eggs/26/001/)  
Stderr for source:  input_files/Wobble-Prot/4-Steered/chain-C/rep2/plumed_test_metad_params.dat   
Download: [zipped raw stdout](plumed_test_metad_params.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_test_metad_params.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file /leonardo_scratch/large/userexternal/tfernand/Projects/Alx-ribo/A-Deprot/chain-C/01_box-min/ref.pdb
[runnervmvrwv9:04493] *** Process received signal ***
[runnervmvrwv9:04493] Signal: Aborted (6)
[runnervmvrwv9:04493] Signal code:  (-6)
[runnervmvrwv9:04493] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6679445330]
[runnervmvrwv9:04493] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f667949eb2c]
[runnervmvrwv9:04493] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f667944527e]
[runnervmvrwv9:04493] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f66794288ff]
[runnervmvrwv9:04493] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f66798a5ff5]
[runnervmvrwv9:04493] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f66798bb0da]
[runnervmvrwv9:04493] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f66798a5a55]
[runnervmvrwv9:04493] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f66798a5a6f]
[runnervmvrwv9:04493] [ 8] plumed_master(+0x146dd)[0x5581122006dd]
[runnervmvrwv9:04493] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f667942a1ca]
[runnervmvrwv9:04493] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f667942a28b]
[runnervmvrwv9:04493] [11] plumed_master(+0x15365)[0x558112201365]
[runnervmvrwv9:04493] *** End of error message ***
</pre>
{% endraw %}
