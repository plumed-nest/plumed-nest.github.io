**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az985-228:68936] *** Process received signal ***
[fv-az985-228:68936] Signal: Aborted (6)
[fv-az985-228:68936] Signal code:  (-6)
[fv-az985-228:68936] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f4fdea42520]
[fv-az985-228:68936] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f4fdea969fc]
[fv-az985-228:68936] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f4fdea42476]
[fv-az985-228:68936] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f4fdea287f3]
[fv-az985-228:68936] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f4fdeea4f26]
[fv-az985-228:68936] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f4fdeeb6d9c]
[fv-az985-228:68936] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f4fdeeb6e07]
[fv-az985-228:68936] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f4fdeeb70bb]
[fv-az985-228:68936] [ 8] plumed(+0x12f48)[0x5606b79b8f48]
[fv-az985-228:68936] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f4fdea29d90]
[fv-az985-228:68936] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f4fdea29e40]
[fv-az985-228:68936] [11] plumed(+0x131e5)[0x5606b79b91e5]
[fv-az985-228:68936] *** End of error message ***
</pre>
{% endraw %}
