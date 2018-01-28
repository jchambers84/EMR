import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JOptionPane;
import javax.swing.JButton;
import java.awt.Font;
import java.awt.SystemColor;
import java.awt.event.ActionListener;
import java.awt.print.PrinterException;
import java.awt.print.PrinterJob;
import java.awt.event.ActionEvent;
import javax.swing.JTextField;
import javax.swing.JLabel;
import javax.swing.JPanel;
import javax.swing.JTextArea;

public class PhysicianFrame {

	private JFrame frame;
	private JTextField lblMessage;
	private JTextField textField;
	private JTextField textField_1;
	private JTextField textField_2;
	private JTextField textField_3;
	private JTextField textField_4;
	private JTextField textField_5;
	private JTextField textField_6;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					PhysicianFrame window = new PhysicianFrame();
					window.frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the application.
	 */
	public PhysicianFrame() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frame = new JFrame();
		frame.getContentPane().setBackground(SystemColor.textHighlight);
		frame.setBounds(0, 0, 800, 689);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.getContentPane().setLayout(null);
		
		JButton btnNewButton = new JButton("Submit Notes");
		btnNewButton.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
			     //JOptionPane.showMessageDialog(null, "Your notes have been successfuly submitted!");
			     lblMessage.setText("Your notes have been successfuly submitted!");
			}
		});
		btnNewButton.setFont(new Font("Times New Roman", Font.BOLD, 14));
		btnNewButton.setBounds(609, 624, 117, 37);
		frame.getContentPane().add(btnNewButton);
		
		lblMessage = new JTextField();
		lblMessage.setBounds(67, 436, 660, 176);
		frame.getContentPane().add(lblMessage);
		lblMessage.setColumns(10);
		
		JLabel lblNewLabel = new JLabel("Physician Notes");
		lblNewLabel.setBounds(71, 408, 106, 16);
		frame.getContentPane().add(lblNewLabel);
		
		JPanel panel = new JPanel();
		panel.setBorder(new LineBorder(new Color(0, 0, 0)));
		panel.setBounds(66, 50, 660, 169);
		frame.getContentPane().add(panel);
		panel.setLayout(null);
		
		JLabel lblNewLabel_2 = new JLabel("Name:");
		lblNewLabel_2.setBounds(6, 18, 61, 16);
		panel.add(lblNewLabel_2);
		
		JLabel lblNewLabel_3 = new JLabel("Current Date:");
		lblNewLabel_3.setBounds(6, 42, 88, 16);
		panel.add(lblNewLabel_3);
		
		JLabel lblNewLabel_4 = new JLabel("DOB:");
		lblNewLabel_4.setBounds(6, 64, 61, 16);
		panel.add(lblNewLabel_4);
		
		textField = new JTextField();
		textField.setBounds(51, 13, 130, 26);
		panel.add(textField);
		textField.setColumns(10);
		
		textField_1 = new JTextField();
		textField_1.setBounds(91, 37, 130, 26);
		panel.add(textField_1);
		textField_1.setColumns(10);
		
		textField_2 = new JTextField();
		textField_2.setBounds(39, 59, 130, 26);
		panel.add(textField_2);
		textField_2.setColumns(10);
		
		JLabel lblMrn = new JLabel("MRN:");
		lblMrn.setBounds(286, 64, 61, 16);
		panel.add(lblMrn);
		
		textField_3 = new JTextField();
		textField_3.setBounds(323, 59, 130, 26);
		panel.add(textField_3);
		textField_3.setColumns(10);
		
		JLabel lblChiefComplaint = new JLabel("Chief Complaint:");
		lblChiefComplaint.setBounds(6, 115, 112, 16);
		panel.add(lblChiefComplaint);
		
		textField_4 = new JTextField();
		textField_4.setBounds(113, 110, 130, 26);
		panel.add(textField_4);
		textField_4.setColumns(10);
		
		JLabel lblVisitDate = new JLabel("Visit Date:");
		lblVisitDate.setBounds(6, 143, 76, 16);
		panel.add(lblVisitDate);
		
		textField_5 = new JTextField();
		textField_5.setBounds(73, 138, 130, 26);
		panel.add(textField_5);
		textField_5.setColumns(10);
		
		JLabel lblPhone = new JLabel("Phone:");
		lblPhone.setBounds(286, 143, 61, 16);
		panel.add(lblPhone);
		
		textField_6 = new JTextField();
		textField_6.setBounds(334, 138, 130, 26);
		panel.add(textField_6);
		textField_6.setColumns(10);
		
		JLabel lblNewLabel_1 = new JLabel("Patient Information");
		lblNewLabel_1.setBounds(66, 22, 135, 16);
		frame.getContentPane().add(lblNewLabel_1);
		
		JPanel panel_1 = new JPanel();
		panel_1.setBorder(new LineBorder(new Color(0, 0, 0)));
		panel_1.setBounds(67, 231, 660, 169);
		frame.getContentPane().add(panel_1);
		panel_1.setLayout(null);
		
		JLabel lblConditionAndDiagnosis = new JLabel("Condition and Diagnosis");
		lblConditionAndDiagnosis.setBounds(244, 6, 163, 16);
		panel_1.add(lblConditionAndDiagnosis);
		
		JTextArea textArea = new JTextArea();
		textArea.setBounds(6, 32, 648, 131);
		panel_1.add(textArea);
		
		Ja();
		textArea.setBounds(6, 32, 648, 131);
		panel_1.add(textArea);
		
		JTextArea textArea_1 = new JTextArea();
		textArea_1.setBounds(6, 23, 648, 146);
		panel_1.add(textArea_1);
		
		JButton btnPrint = new JButton("Print");
		btnPrint.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				 PrinterJob job = PrinterJob.getPrinterJob();
		       
		         boolean ok = job.printDialog();
		         if (ok) {
		             try {
		                  job.print();
		             } catch (PrinterException ex) {
		              /* The job did not successfully complete */
		             }
		         }
		    }
			
		});
		btnPrint.setBounds(67, 632, 117, 29);
		frame.getContentPane().add(btnPrint);
	}
}
