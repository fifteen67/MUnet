Reviewer package (inference only, confidential)

Generated at:
F:\reproduction2.0\MUNET3.18\reviewer_package_12methods_confidential_20260408

Quick start
1) Install Python 3.10+ (or Conda).
2) Install dependencies:
   pip install -r requirement.txt
3) Run:
   - ReviewerUI.exe (recommended)
   - run.cmd (fallback)
4) In UI, select a method and click "Run Inference (5 samples)".
5) Results are saved to:
   outputs_ui/<MethodName>/

Important
- This package does not include .py source files for inference.
- Inference scripts are provided as bytecode in shared_inference_code_pyc_only/.
- fair9 and tryA are different branches; do not mix them into one fairness table.

Contents
1) methods/ (12 methods, each with weights_or_params and notes)
2) sample_test_images_5_munet2_best/ (5 test cases)
3) shared_inference_code_pyc_only/ (bytecode inference modules)
4) metric_sources/ (source metric files)
5) metrics_summary.csv (method-level summary table)
6) manifest.json (package manifest)
