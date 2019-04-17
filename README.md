# TDTU_CMUSPHINX_REPORT

CMU Speech Processing demo - Ton Duc Thang University

Step 1: Install python

Step 2: Install perl

Step 3: Check perl by using: perl -v 
		and python by using: python -V
		
Step 4: cd ...\TDTU_CMUSphinx_Report\other - run cmd
		run: python ../sphinxtrain/scripts/sphinxtrain -t other setup

Step 5: Modify sphinx_train.cfg in etc

Step 6: cd ...\TDTU_CMUSphinx_Report\other - run cmd
		run: python ../sphinxtrain/scripts/sphinxtrain run
		
Step 7: cd ...\TDTU_CMUSphinx_Report\pocketsphinx\bin\Release\Win32 - run cmd
		run: pocketsphinx_continuous -inmic "yes" -hmm "...\output\other.ci_cont" -dict "...\output\other.dic" -lm "...output\other.lm.DMP"

