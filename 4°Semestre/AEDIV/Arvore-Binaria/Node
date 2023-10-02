package binary_tree;

public class Node {

		int item;
		Node right;
		Node left;
		
		public Node(int item) {
			this.item = item;
			this.right = null;
			this.left = null;
		}
		
		public void Insert(int item) {
			if(item < this.item) {
				if(this.left != null) {
					this.left.Insert(item);					
				}else{
					this.left = new Node(item);
				}
			}else {
				if(this.right != null) {
					this.right.Insert(item);
				}else {
					this.right = new Node(item);
				}
			}
		}
		
		public void Insert_descending(int item) {
			if(item > this.item) {
				if(this.left != null) {
					this.left.Insert_descending(item);					
				}else{
					this.left = new Node(item);
				}
			}else {
				if(this.right != null) {
					this.right.Insert_descending(item);
				}else {
					this.right = new Node(item);
				}
			}
		}
		
		public void Print_in_order(Node trab) {
			if(trab.left != null){
				trab.Print_in_order(trab.left);
			}
			System.out.println(trab.item);
			
			if(trab.right != null) {
				trab.Print_in_order(trab.right);
			}
		}
		
		public void Print_in_pre_order(Node trab) {
			System.out.println(trab.item);
			if(trab.left != null){
				trab.Print_in_pre_order(trab.left);
			}
			if(trab.right != null) {
				trab.Print_in_pre_order(trab.right);
			}
		}
		
		public void Print_in_post_order(Node trab){
			if(trab.left != null){
				trab.Print_in_post_order(trab.left);
			}
			
			if(trab.right != null) {
				trab.Print_in_post_order(trab.right);
			}
			System.out.println(trab.item);	
		}
}
