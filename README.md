# MOSFETG
高速 MOSFET 型号推荐（按10M Ghz频率级别）
BFR540	高达 1.5 GHz	-	SOT-23	RF 小功率 NPN 晶体管，但用作激光小信号调制也可

FDV301N	~100 MHz+	1.5 Ω	SOT-23	极快开关，适合低压小功率调制

IRF530N / IRFZ44N	~500 kHz（太慢，不推荐）	-	TO-220	不适合激光调制

FQPF50N06	~1 MHz 实测	60V/50A	TO-220	仍太慢

NXP BUK7Y12-55B	~50 MHz 实际使用	11 mΩ	LFPA

GaN 系列（强烈推荐）	>100 MHz 到 1 GHz+	<50 mΩ	DFN/QFN	超快开关，适合激光调制、毫米波通信
