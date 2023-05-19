question = QLabel('В каком году была основана алгоритмика?')
btn_answer1 = QRadioButton('2013')
btn_answer2 = QRadioButton('2010')
btn_answer3 = QRadioButton('2016')
btn_answer4 = QRadioButton('2019')
layout_main = QVBoxLayout
layout_main.addWidget(question, alignment = Qt.AlignCenter)
layout_main.addWidget(btn_answer1, alignment = Qt.AlignCenter)
layout_main.addWidget(btn_answer2, alignment = Qt.AlignCenter)
layout_main.addWidget(btn_answer3, alignment = Qt.AlignCenter)
layout_main.addWidget(btn_answer4, alignment = Qt.AlignCenter)
layoutH1 = QHBoxLayout
layoutH2 = QHBoxLayout
layoutH3 = QHBoxLayout
layoutH1.addWidget(question, alignment = Qt.AlignCenter)
layoutH1.addWidget(btn_answer1, alignment = Qt.AlignCenter)
layoutH1.addWidget(btn_answer2, alignment = Qt.AlignCenter)
layoutH1.addWidget(btn_answer3, alignment = Qt.AlignCenter)
layoutH1.addWidget(btn_answer4, alignment = Qt.AlignCenter)
layout_main = QVBoxLayout()
layout_main.addLayout(layoutH1)
layout_main.addLayout(layoutH2)
layout_main.addLayout(layoutH3)
main_win.setLayout(layout_main)
