%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%% | RAFTS3groups - Rapid Alignment Free Tool for Sequences Similarity Search to Groups| %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%   clustering algoritm to create homology clusters based on RAFTS3 (VIALLE, R. A.) 
%   More informations about RAFTS3 in: https://sourceforge.net/projects/rafts3/
%   copyright (c) 2018  Federal University of Parana
%   Setor de Educação Profissional e Tecnológica da UFPR - Laboratório de Bioinformática 
%   Pós-graduação em Bioinformática
%   Universidade Federal do Paraná - UFPR
%   Rua Dr. Alcides Vieira Arco-verde, 1225 
%   CEP: 81520-260 Jardim das Américas
%   Curitiba – PR  
%   Brasil
%   
%   Developers and colaborations team:
%   Roberto T. Raittz (raittz@gmail.com)
%   Bruno T. L. Nichio (brnichio@gmail.com)
%   Ricardo A. Vialle (ricardovialle@gmail.com)
%   Jeroniza N. Marchaukoski (jeroniza@ufpr.br)
%   Nilson A. R. Coimbra (nilson.coimbra@gmail.com)
%   Alexandre Q. Lejambre (lejambre@gmail.com)
%   Aryel Marlus Repula de Oliveira (aryelmarlus@gmail.com)
%   Camilla R. Pierri (camilla_kaori@hotmail.com)
%   Leticia G. C. Santos (grazielalcs@gmail.com)
%   Fabio O. Pedrosa (fpedrosa@ufpr.br)
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
rafts3g.exe - version 2.0 compilated by MATLAB version R2012b (v8.0.0) 

Command line (by terminal) = rafts3g file, nself, varargin


Variables:
file = file in FASTA or multiFASTA format from nucleotides or aminoacids
nself = limiar de selfscore. Exemple: nself = 0.5 ( the sequences will be clustering with 50% of similarity between the sequences )
varargin = 1; if the sequences in FASTA format are Nucleotides
varargin = 2; if the sequences in FASTA format are Aminoacids

Outputs: 
Default, three outputs:
path\RAFTS3Clusters\allClusters.fasta (all clusters in a unique FASTA format)
path\RAFTS3Clusters\Cluster_n.fasta (each cluster separated in format FASTA)
path\rafts3gresult.mat ( MATLAB matrix with parameters configurations)

%IMPORTANT:
The executable depends the MatLab Compiler Runtime (MCR) version 8.0.0 (built MATLAB vers. 2012b).
