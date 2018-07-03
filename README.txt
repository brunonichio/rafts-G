%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%% | RAFTS³G- Rapid Alignment Free Tool for Sequences Similarity Search to Groups| %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%   clustering algorithm to create homolog clusters based on RAFTS3 (VIALLE, R. A.) 
%   More informations about RAFTS3 disponible at: https://sourceforge.net/projects/rafts3/
%   Setor de Educação Profissional e Tecnológica da UFPR - Laboratório de Bioinformática 
%   Postgraduate in Bioinformatics
%   Universidade Federal do Paraná - UFPR
%   Rua Dr. Alcides Vieira Arco-verde, 1225 
%   CEP: 81520-260 Jardim das Américas
%   Curitiba – PR  
%   Brasil
%   
%   Developers and colaboration team:
%   Roberto T. Raittz (raittz@gmail.com)
%   Bruno T. L. Nichio (brnichio@gmail.com)
%   Ricardo A. Vialle (ricardovialle@gmail.com)
%   Jeroniza N. Marchaukoski (jeroniza@ufpr.br)
%   Alexandre Q. Lejambre (lejambre@gmail.com)
%   Aryel Marlus Repula de Oliveira (aryelmarlus@gmail.com)
%   Camilla R. Pierri (camilla_kaori@hotmail.com)
%   Leticia G. C. Santos (grazielalcs@gmail.com)
%   Fabio O. Pedrosa (fpedrosa@ufpr.br)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
RAFTS3G.exe - version 2.0 compilated by MATLAB version R2017a (v9.2) 

Command line (by terminal) = RAFTS3G.exe file nself varargin "C:\MCR_v9.2_dir"


Variables:
file = file in FASTA or multiFASTA format from nucleotides or aminoacids
nself = limiar de selfscore. Exemple: nself = 0.5 ( the sequences will be clustering with 50% of similarity between the sequences )
varargin = 1; if the sequences in FASTA format are Nucleotides
varargin = 2; if the sequences in FASTA format are Aminoacids

**(Example: RAFTS3G.exe a.faa 0.5 2 "C:\Program Files\MATLAB\MATLAB Compiler Runtime\v92")**

Outputs: 
Default, three outputs:
path\RAFTS3Clusters\allClusters.fasta (all clusters in a unique FASTA format)
path\RAFTS3Clusters\Cluster_n.fasta (each cluster separated in format FASTA)
path\rafts3gresult.mat ( MATLAB matrix with parameters configurations)

%IMPORTANT:
The executable depends the MatLab Compiler Runtime (MCR) version 9.2 (built MATLAB vers. 2017a).
