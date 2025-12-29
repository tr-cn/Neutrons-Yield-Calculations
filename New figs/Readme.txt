In this folder, I changes the FontSize

close all; clc; clear;
open('Electrons.fig');ax_e = gca;  electrons_fig = gcf;
ax_e.FontSize = 46;
ax_e.YLabel.FontSize = 56;
ax_e.XLabel.FontSize = 56;
open('Neutrons.fig');ax_n = gca; neutrons_fig = gcf;
ax_n.FontSize = 46;
ax_n.YLabel.FontSize = 56;
ax_n.XLabel.FontSize = 56;


ax_e.Units = "normalized";  ax_n.Units = "normalized";
ax_n.YLabel.Units = "normalized"; ax_e.YLabel.Units = "normalized";
ax_n.YLabel.VerticalAlignment = "top"; ax_e.YLabel.VerticalAlignment = "top";
ax_n.YLabel.Interpreter = "latex";
ax_n.YLabel.Position(1) = -0.1732;

ax_e.YLabel.Position(1) = ax_n.YLabel.Position(1);
