# docsify

hello docsify

# hello1

1231

afaf

ewqerqwe

```java
public class LinkedListImpl<T> implements LinkedList<T> {

    private LinkedListNode<T> head;
    private LinkedListNode<T> tail;

    public LinkedListImpl() {
        this.head = null;
        this.tail = null;
    }

    @Override
    public LinkedList<T> append(T value) {
        final LinkedListNode<T> newNode = new LinkedListNode<>(value);
        // head为空
        if (this.head == null) {
            this.head = newNode;
            this.tail = newNode;
            return this;
        }

        this.tail.setNext(newNode);
        this.tail = newNode;

        return this;
    }

    @Override
    public LinkedList<T> prepend(T value) {
        final LinkedListNode<T> newNode = new LinkedListNode<>(value, head);
        this.head = newNode;

        if (this.tail == null) {
            this.tail = newNode;
        }
        return this;
    }

    @Override
    public LinkedListNode<T> delete(T value) {
        return null;
    }

    @Override
    public LinkedListNode<T> find(T value) {
        return null;
    }

    @Override
    public LinkedListNode<T> deleteTail() {

        return null;
    }

    @Override
    public LinkedListNode<T> deleteHead() {
        return null;
    }

    @Override
    public LinkedList<T> fromArray(T[] values) {
        return null;
    }

    @Override
    public T[] toArray() {
        return null;
    }

    @Override
    public LinkedList<T> reverse() {
        return null;
    }
}
```

# hello2

1231

afaf

ewqerqwe


# hello3

1231

afaf

ewqerqwe


# hello4

1231

afaf

ewqerqwe

