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
[runnervm76f27:04532] *** Process received signal ***
[runnervm76f27:04532] Signal: Aborted (6)
[runnervm76f27:04532] Signal code:  (-6)
[runnervm76f27:04532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a15845330]
[runnervm76f27:04532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a1589ec0c]
[runnervm76f27:04532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a1584527e]
[runnervm76f27:04532] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a158288ff]
[runnervm76f27:04532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a15ca5ff5]
[runnervm76f27:04532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a15cbb0da]
[runnervm76f27:04532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a15ca5a55]
[runnervm76f27:04532] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a15ca5a6f]
[runnervm76f27:04532] [ 8] plumed(+0x146dd)[0x5594715a56dd]
[runnervm76f27:04532] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a1582a1ca]
[runnervm76f27:04532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a1582a28b]
[runnervm76f27:04532] [11] plumed(+0x15365)[0x5594715a6365]
[runnervm76f27:04532] *** End of error message ***
</pre>
{% endraw %}
