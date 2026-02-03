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
[runnervmkj6or:04278] *** Process received signal ***
[runnervmkj6or:04278] Signal: Aborted (6)
[runnervmkj6or:04278] Signal code:  (-6)
[runnervmkj6or:04278] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5bf7445330]
[runnervmkj6or:04278] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5bf749eb2c]
[runnervmkj6or:04278] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5bf744527e]
[runnervmkj6or:04278] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5bf74288ff]
[runnervmkj6or:04278] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5bf78a5ff5]
[runnervmkj6or:04278] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5bf78bb0da]
[runnervmkj6or:04278] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5bf78a5a55]
[runnervmkj6or:04278] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5bf78a5a6f]
[runnervmkj6or:04278] [ 8] plumed(+0x146dd)[0x558af572a6dd]
[runnervmkj6or:04278] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5bf742a1ca]
[runnervmkj6or:04278] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5bf742a28b]
[runnervmkj6or:04278] [11] plumed(+0x15365)[0x558af572b365]
[runnervmkj6or:04278] *** End of error message ***
</pre>
{% endraw %}
