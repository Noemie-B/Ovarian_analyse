# Ovarian_analyse

1. Patches creation : https://github.com/Noemie-B/Ovarian_analyse/blob/main/1_patches_wsi.ipynb.
   Thanks to https://nbviewer.org/github/afiliot/TPDUIA/blob/main/TPDUIA/2022/whole_slide_images.ipynb for patch extraction file !  
3. Nuclei segmentation and classification with HoVer-Net (PanNuke weights) : https://github.com/simongraham/hovernet_inference  
4. Nuclei count per patch + sort patches to select the most interesting ones : https://github.com/Noemie-B/Ovarian_analyse/blob/main/3_Count_filtering%2Bsort_patch_pixels_number.ipynb  
5. - PyRadiomics features extraction : https://github.com/Noemie-B/Ovarian_analyse/blob/main/4_1_Pyradiomics.ipynb.  
   - PyRadiomics package  : https://pyradiomics.readthedocs.io/en/latest/.  
   - Classification with PyRadiomics values : https://github.com/Noemie-B/Ovarian_analyse/blob/main/5_Classification_with_PyRadiomics_values.html.
   - For the html viewer : https://htmlviewer.github.io/  
7. - Athena select patches : https://github.com/Noemie-B/Ovarian_analyse/blob/main/4_2a_Athena_select_patches_size.ipynb  
   - Athena object creation : https://github.com/Noemie-B/Ovarian_analyse/blob/main/4_2b_Creation_object_so_PANNUKE.ipynb  
   - Athena analysis : https://github.com/Noemie-B/Ovarian_analyse/blob/main/4_2c__Athena-Ovarian_analysis_PANNUKE.ipynb  
   - Athena package : https://github.com/AI4SCR/ATHENA/blob/master/tutorials/overview.ipynb  
8. - Patches classification with Slideflow : https://github.com/Noemie-B/Ovarian_analyse/blob/main/5_Classification_with_Slideflow.ipynb  
   - Results : https://github.com/Noemie-B/Ovarian_analyse/blob/main/5_results_Slideflow.ipynb  
   - Slideflow package: https://github.com/jamesdolezal/slideflow  

## Disclaimer
The results and analyses presented in this repository are intended for research purposes only. They are not validated for clinical use and should not be used to diagnose, treat, or manage any health conditions. Always consult with a qualified healthcare professional for medical advice and treatment.

## License
# License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/'>http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is distributed under the the terms of the creative commons attribution <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/'>http://creativecommons.org/licenses/by-nc-sa/4.0/">Licence Creative Commons Attribution - No commercial use - shared in the same conditions 4.0 International</a>.

## Copyright (c) 

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
