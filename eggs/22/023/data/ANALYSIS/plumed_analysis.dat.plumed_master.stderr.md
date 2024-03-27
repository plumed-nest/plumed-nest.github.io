**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:89) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az985-228:68944] *** Process received signal ***
[fv-az985-228:68944] Signal: Aborted (6)
[fv-az985-228:68944] Signal code:  (-6)
[fv-az985-228:68944] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fef19a42520]
[fv-az985-228:68944] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fef19a969fc]
[fv-az985-228:68944] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fef19a42476]
[fv-az985-228:68944] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fef19a287f3]
[fv-az985-228:68944] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7fef19ea4f26]
[fv-az985-228:68944] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7fef19eb6d9c]
[fv-az985-228:68944] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7fef19eb6e07]
[fv-az985-228:68944] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fef19eb70bb]
[fv-az985-228:68944] [ 8] plumed_master(+0x12e7f)[0x55796515de7f]
[fv-az985-228:68944] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fef19a29d90]
[fv-az985-228:68944] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fef19a29e40]
[fv-az985-228:68944] [11] plumed_master(+0x13115)[0x55796515e115]
[fv-az985-228:68944] *** End of error message ***
</pre>
{% endraw %}
