**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az985-228:68967] *** Process received signal ***
[fv-az985-228:68967] Signal: Aborted (6)
[fv-az985-228:68967] Signal code:  (-6)
[fv-az985-228:68967] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f40baa42520]
[fv-az985-228:68967] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f40baa969fc]
[fv-az985-228:68967] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f40baa42476]
[fv-az985-228:68967] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f40baa287f3]
[fv-az985-228:68967] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f40baea4f26]
[fv-az985-228:68967] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f40baeb6d9c]
[fv-az985-228:68967] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f40baeb6e07]
[fv-az985-228:68967] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f40baeb70bb]
[fv-az985-228:68967] [ 8] plumed(+0x12f48)[0x55d869724f48]
[fv-az985-228:68967] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f40baa29d90]
[fv-az985-228:68967] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f40baa29e40]
[fv-az985-228:68967] [11] plumed(+0x131e5)[0x55d8697251e5]
[fv-az985-228:68967] *** End of error message ***
</pre>
{% endraw %}
