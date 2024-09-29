<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp"
    android:background="@android:color/white">


    <TextView
        android:id="@+id/header"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Food"
        android:textSize="24sp"
        android:textStyle="bold"
        android:layout_gravity="center"
        android:layout_marginBottom="8dp"/>


    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_marginBottom="16dp">

        <TextView
            android:id="@+id/budget"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Budget: 5000"
            android:textStyle="bold"
            android:textSize="18sp"
            android:layout_marginEnd="16dp"/> <!-- Space between budget and expense -->

        <TextView
            android:id="@+id/expense"
            android:layout_width="0dp"
            android:layout_height="wrap_content"
            android:layout_weight="1"
            android:text="Expense: 2350"
            android:textStyle="bold"
            android:textSize="18sp"/>
    </LinearLayout>
    <TableLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:stretchColumns="1"
        android:layout_marginTop="16dp"
        android:background="@android:color/white">


        <TableRow>
            <TextView
                android:id="@+id/Desription"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Description"
                android:textStyle="bold"
                android:gravity="center"
                android:padding="8dp"
                android:background="@drawable/cell_border" />

            <TextView
                android:id="@+id/DateInput"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Date"
                android:textStyle="bold"
                android:gravity="center"
                android:padding="8dp"
                android:background="@drawable/cell_border" />

            <TextView
                android:id="@+id/amountInput"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Amount"
                android:textStyle="bold"
                android:gravity="center"
                android:padding="8dp"
                android:background="@drawable/cell_border" />
        </TableRow>


        <TableRow>
            <EditText
                android:id="@+id/descriptionInput2"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="Natraj Hotel"
                android:padding="8dp"
                android:background="@drawable/cell_border" />

            <EditText
                android:id="@+id/dateInput2"
                android:layout_width="0dp"
                android:layout_height="match_parent"
                android:layout_weight="1"
                android:background="@drawable/cell_border"
                android:text="13-03-2024"
                android:minHeight="48dp"
                android:padding="8dp" />

            <EditText
                android:id="@+id/amountInput2"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="900"
                android:inputType="numberDecimal"
                android:padding="8dp"
                android:background="@drawable/cell_border" />
        </TableRow>
        <TableRow>
            <EditText
                android:id="@+id/descriptionInput3"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="Kuber Hotel"
                android:padding="8dp"
                android:background="@drawable/cell_border" />

            <EditText
                android:id="@+id/dateInput3"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="02-06-2004"
                android:clickable="true"
                android:focusable="false"
                android:padding="8dp"
                android:background="@drawable/cell_border" />

            <EditText
                android:id="@+id/amountInput3"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="850"
                android:inputType="numberDecimal"
                android:padding="8dp"
                android:background="@drawable/cell_border" />
        </TableRow>
        <TableRow>
            <EditText
                android:id="@+id/descriptionInput4"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="Kokos Hotel"
                android:padding="8dp"
                android:background="@drawable/cell_border" />

            <EditText
                android:id="@+id/dateInput4"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="29-09-2024"
                android:clickable="true"
                android:focusable="false"
                android:padding="8dp"
                android:background="@drawable/cell_border" />

            <EditText
                android:id="@+id/amountInput4"
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:minHeight="48dp"
                android:text="600"
                android:inputType="numberDecimal"
                android:padding="8dp"
                android:background="@drawable/cell_border" />
        </TableRow>
        <TableRow>

            <TextView
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:padding="8dp"
                android:gravity="center"/>

            <TextView
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:text="Total"
                android:textStyle="bold"
                android:gravity="center"
                android:padding="8dp"
                android:background="@drawable/cell_border" />
            <TextView
                android:layout_width="0dp"
                android:layout_height="wrap_content"
                android:layout_weight="1"
                android:padding="8dp"
                android:gravity="center"
                android:text="2350"
                android:background="@drawable/cell_border" />


        </TableRow>


    </TableLayout>
</LinearLayout>





