1) Computational outputs from SF model 

1-1) Comparisons with laboratory experiments
Folder "case A": Computational outputs for the comparisons with laboratory experiments

1-2) 1/0.01 shoot/m^2 & water depth = 0.5 m
Folder "uniform_flow_600shoot0.0100m_z0.5m_u0.05": flow velocity = 0.05 m/s
Folder "uniform_flow_600shoot0.0100m_z0.5m_u0.10": flow velocity = 0.10 m/s
Folder "uniform_flow_600shoot0.0100m_z0.5m_u0.20": flow velocity = 0.20 m/s

1-3) 1/0.01 shoot/m^2 & water depth = 1.0 m
Folder "uniform_flow_600shoot0.0100m_z1.0m_u0.05": flow velocity = 0.05 m/s
Folder "uniform_flow_600shoot0.0100m_z1.0m_u0.10": flow velocity = 0.10 m/s
Folder "uniform_flow_600shoot0.0100m_z1.0m_u0.20": flow velocity = 0.20 m/s

1-4) 1/0.01 shoot/m^2 & water depth = 1.5 m
Folder "uniform_flow_600shoot0.0100m_z1.5m_u0.05": flow velocity = 0.05 m/s
Folder "uniform_flow_600shoot0.0100m_z1.5m_u0.10": flow velocity = 0.10 m/s
Folder "uniform_flow_600shoot0.0100m_z1.5m_u0.20": flow velocity = 0.20 m/s

1-5) 1/0.0225 shoot/m^2 & water depth = 0.5 m
Folder "uniform_flow_600shoot0.0225m_z0.5m_u0.05": flow velocity = 0.05 m/s
Folder "uniform_flow_600shoot0.0225m_z0.5m_u0.10": flow velocity = 0.10 m/s
Folder "uniform_flow_600shoot0.0225m_z0.5m_u0.20": flow velocity = 0.20 m/s

1-6) 1/0.0225 shoot/m^2 & water depth = 1.0 m
Folder "uniform_flow_600shoot0.0225m_z1.0m_u0.05": flow velocity = 0.05 m/s
Folder "uniform_flow_600shoot0.0225m_z1.0m_u0.10": flow velocity = 0.10 m/s
Folder "uniform_flow_600shoot0.0225m_z1.0m_u0.20": flow velocity = 0.20 m/s

1-7) 1/0.0225 shoot/m^2 & water depth = 1.5 m
Folder "uniform_flow_600shoot0.0225m_z1.5m_u0.05": flow velocity = 0.05 m/s
Folder "uniform_flow_600shoot0.0225m_z1.5m_u0.10": flow velocity = 0.10 m/s
Folder "uniform_flow_600shoot0.0225m_z1.5m_u0.20": flow velocity = 0.20 m/s

2) Difference in horizontal and vertical distances of seagrass blades between the SF model and laboratory experiment
Excel file, "profile_eelgrass.xlsx"

3) Format of computatinal outputs

3-1) filename, "amamo0###00-000###.dat", #: 0-9
row 1: "horizontal distance of node 0"	"vertical distance of node 0"	"horizontal velocity of node 0"	"vertical velocity of node 0"
row 2: "horizontal distance of node 1"	"vertical distance of node 1"	"horizontal velocity of node 1"	"vertical velocity of node 1"
row 3: "horizontal distance of node 2"	"vertical distance of node 2"	"horizontal velocity of node 2"	"vertical velocity of node 2"
-----	-----	-----	-----
row 20: "horizontal distance of node 19"	"vertical distance of node 19"	"horizontal velocity of node 19"	"vertical velocity of node 19"
ro w21: "horizontal distance of node 20"	"vertical distance of node 20"	"horizontal velocity of node 20"	"vertical velocity of node 20"

3-2) filename, "amamo_uniform-0###00.txt", #: 0-9, for "1-1)"
row 1: time	"computational time"
row 2: dz	"vertical mesh interval from the bottom to the top of computational domain"
row 3: limit_depth	0.001
row 4: items	number	k_offset	center_x	center_y	delta_x	delta_y	btm_k	sfc_k	btm_z	sfc_z	container_i	container_j	local_i	local_j	dry_wet
row 5 up to row 579: column	"corresponding number to row4"
row 580 up to row 1154: "column number"	salinity	"salinity at each vertical mesh"
row 1155 up to row 1729: "column number"	v	"width direction velocity at each vertical mesh"
row 1730 up to row 2304: "column number"	psi	"dissipation at each vertical mesh"
row 2305 up to row 2879: "column number"	u	"horizontal velocity at each vertical mesh"
row 2880 up to row 3454: "column number"	w	"vertical velocity at each vertical mesh"
row 3455 up to row 4029: "column number"	tke	"turbulent kinetic energy at each vertical mesh"
row 4030 up to row 4604: "column number"	temperature	"temperature at each vertical mesh"
row 4605 up to row 5179: "column number"	density	"density at each vertical mesh"
row 5180 up to row 5754: "column number"	pressure	"pressure at each vertical mesh"
row 5755 up to row 6329: "column number"	eddy_viscosity	"eddy_viscosity at each vertical mesh"
row 6330 up to row 6904: "column number"	eddy_viscosity	"eddy_viscosity at each vertical mesh"

3-3) filename, "amamo_uniform-0###00.txt", #: 0-9, for 1/0.01 shoot/m^2 and 1/0.0225 shoot/m^2
row 1: time	"computational time"
row 2: dz	"vertical mesh interval from the bottom to the top of computational domain"
row 3: limit_depth	0.001
row 4: items	number	k_offset	center_x	center_y	delta_x	delta_y	btm_k	sfc_k	btm_z	sfc_z	container_i	container_j	local_i	local_j	dry_wet
row 5 up to row 1304: column	"corresponding number to row4"
row 1305 up to row 2604: "column number"	salinity	"salinity at each vertical mesh"
row 2605 up to row 3904: "column number"	v	"width direction velocity at each vertical mesh"
row 3905 up to row 5204: "column number"	psi	"dissipation at each vertical mesh"
row 5205 up to row 6504: "column number"	u	"horizontal velocity at each vertical mesh"
row 6505 up to row 7804: "column number"	w	"vertical velocity at each vertical mesh"
row 7805 up to row 9104: "column number"	tke	"turbulent kinetic energy at each vertical mesh"
row 9105 up to row 10404: "column number"	temperature	"temperature at each vertical mesh"
row 10405 up to row 11704: "column number"	density	"density at each vertical mesh"
row 11705 up to row 13004: "column number"	pressure	"pressure at each vertical mesh"
row 13005 up to row 14304: "column number"	eddy_viscosity	"eddy_viscosity at each vertical mesh"
row 14305 up to row 15604: "column number"	eddy_viscosity	"eddy_viscosity at each vertical mesh"
