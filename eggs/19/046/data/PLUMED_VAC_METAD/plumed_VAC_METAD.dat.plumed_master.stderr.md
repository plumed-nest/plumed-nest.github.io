**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC_METAD/plumed_VAC_METAD.dat   
(download [zipped raw stdout](plumed_VAC_METAD.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: FPS LABEL=fps REFERENCE=Faidon_new_ref.pdb LIGAND=lig ANCHOR=2481 POINTS=-0.5910,0.3486,-1.6694,-0.6214,0.5475,-1.2516
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f0f152a64b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f0f152a6428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f0f152a802a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f0f158e084d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f0f158de6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f0f158de701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f0f158de969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f0f15291830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14163] *** End of error message ***
</pre>
{% endraw %}
