# Linked-Binary-Heaps
Implement a priority queue using a heap-ordered binary tree, but use a triply linked structure instead of an array. You will need three links per node: two to traverse down the tree and one to traverse up the tree to the node's parent. Your implementation should guarantee logarithmic running time per operation, even if no maximum priority-queue size is known ahead of time.
Please use the following API for your ADT:
public interface MaxPQ<T extends Comparable<T>> {
  T dequeue();
  void enqueue(T key);
  boolean isEmpty();
  int size();
  String toString();
}
